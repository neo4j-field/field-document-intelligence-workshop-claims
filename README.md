# Document Intelligence Workshop - Claims

### From Unstructured to Structured, Build an Agent Ready Graph with Neo4j

For this workshop we simulate working with data for a Health Claims Processing use case. We have structured data from our “relational” system, for 100 Claims. Information here includes data on the Patient, Claim, Provider, Payer, Procedure, and Diagnosis. 

Along with this structured data, we have unstructured data in the form of doctors’ notes. These are pdf files that were stored in our SharePoint system that are related to these claims. 

Currently a person has to manually examine the notes in relation to the structured data to validate that procedure and diagnosis codes in the notes match what was filed in the claim.  Processing can take time and sometimes as a result, errors are made. By connecting the data in Neo4j and leveraging LLMs, we can accelerate and automate the review process, providing value in time and money to patients, providers, and the business. In this workshop we use. Neo4j

**Document Intelligence to:**
- Create a data model for our pdf files.
- Extract the doctor’s notes text from our pdf files in import them into the data model.

**LOAD CSV to**
- Load our structured data and connect it with the unstructured. 

In this way you’ll see how Neo4j is used to connect the unstructured and structured. How we can append to an existing graph and continue to enrich it. 

**Query our connected data using GraphRAG**
- Query the text embeddings extracted from the unstructured data for semantic similarity search 
- Query the text embeddings along with relationships and other connected nodes to perform VectorCypher retrieval for GraphRag 

**Build and Deploy and Aura Agent**
- Create an agent with tools so we can use natural language to interact with the graph we’ve created.

All that is required to get started is a free instance of Aura. [You can sign up for that here.](https://console-preview.neo4j.io/)

The Document-Intelligence-Workshop-Claims.pdf contains a walkthrough of the actions to take in Aura to accomplish the tasks outline above.
