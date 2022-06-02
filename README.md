# Social-Network-and-Lifestyle-Recommendation

1) Introduction

2) Data source
   We create questionnaire in Google Form to collect about personal preferences including domicile, travel, social media, food, game, football club, buffet restaurant, TV series, movie and actor. The questionnaires were sent to 14 people.
   Next, we cleansing the answers and use the answers to create a knowledge graph. We got 378 unique nodes and 1276 edges with 12 types of edge in knowledge graphs.
   
3) Graph database
   We store the knowledge graph in graph database (GDB) called [Neo4j](https://neo4j.com/). We run python script to query with [cypher](https://neo4j.com/developer/cypher/), Neo4j’s graph query language, on [Neo4j sandbox](https://neo4j.com/sandbox/) to store the knowledge graph and return graph for embadding.  
   - Example graph  
   ![example_graph](./img/example_graph.png)
