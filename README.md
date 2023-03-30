# Detecting narrative perspectives
The goal of this research project is to extract multiple narrations of news events from existing KGs such as DBpedia, Wikidata, EventKG by using a formal structure presented in a paper. The project proposes to build an ontology based on this formalization, identify sets of facts in the KGs to instantiate the ontology, and use SPARQL to visualize and explore the data. The research methodology involves identifying similar narratives that represent the same event from different perspectives using a rule-based approach or clustering methods such as KG embeddings. A minimal evaluation for the approach is also proposed. Resources such as Google Drive, Notion, WebVOWL, and Overleaf are provided to support the project.

# How the repo is built
The repository contains various resources that were utilized during the research project. The repository consists of four primary folders: The ontology file, SPARQL queries, Python files, and a README file. The folders contain the following information:
-The ontology file is presented in TTL format and includes the main ontology, news outlets, and Wikidata KG in turtle format. These files can be uploaded to GraphDB to visualize the corresponding KGs.
- The SPARQL queries file includes the primary SPARQL queries used to retrieve the main research results. These queries can be copied and pasted into the GraphDB SPARQL interface to obtain the same outcomes.
-The Python files are used to create visualizations based on the results from the aforementioned SPARQL queries.
