# Detecting narrative perspectives
_Research goal:_ News and events can be narrated according to different perspectives (e.g. “a coup” and “a revolution” are two faces of the same medal). The goal of this project is to extract narrations (in terms of set of triples/facts) from existing KGs such as DBpedia, Wikidata, EventKG, and reconstruct an event in its multiple facets. In order to collect these facts, we will use the narrative formal structure as presented in this paper Links to an external site..

_Background:_ also read this paper Links to an external site.and this paper Links to an external site..

## Build your infrastructure
1. Build an ontology (classes + relationships) based on the formalisation presented [in this paper](http://ceur-ws.org/Vol-2969/paper31-CAOS.pdf).
2. Identify sets of facts in one or more KG of your choice to instantiate the ontology (i.e. set of facts that belong to a given part of the classes you defined)
3. Use SPARQL to visualise and explore your data  

## Draw your research around 
1. Method: starting from the model you created, draw a method to identify similar narratives which might represent the same event under different perspectives. You could use a rule-based approach (AnyBurl) or clustering methods such as KG embeddings. 
2. Evaluation: define a minimal evaluation for your approach.
