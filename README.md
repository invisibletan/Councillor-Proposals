# SubQuery - Starter Package


The Starter Package is an example that you can use as a starting point for developing your SubQuery project.
A SubQuery package defines which data The SubQuery will index from the Substrate blockchain, and how it will store it. 

# Query the project

Open your browser and head to `http://localhost:3000`.

Finally, you should see a GraphQL playground is showing in the explorer and the schemas that ready to query.

For the `subql-starter` project, you can try to query with the following code to get a taste of how it works.

````graphql
{
  query{
    starterEntities(first:10){
      nodes{
        field1,
        field2,
        field3
      }
    }
  }
}
````
# Result
![Result](/src/Capture.PNG)
# Councillor-Proposals
