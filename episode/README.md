# GraphQL Character Query by episode

## Objective
This task focuses on writing GraphQL queries to retrieve specific character information using their ID. The queries fetch details for characters with IDs 1, 2, 3, and 4 from a GraphQL API.

## Endpoint
The queries are designed for the Rick and Morty GraphQL API: `https://rickandmortyapi.com/graphql`. You can test these queries using tools like GraphiQL or Postman.

## Queries
Each query targets the `character(id: ID!)` field and retrieves the following fields:
- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

## Files
- `character-id-1.graphql` & `character-id-1-output.json`: Query and output for character ID 1.
- `character-id-2.graphql` & `character-id-2-output.json`: Query and output for character ID 2.
- `character-id-3.graphql` & `character-id-3-output.json`: Query and output for character ID 3.
- `character-id-4.graphql` & `character-id-4-output.json`: Query and output for character ID 4.

## How to Run
1. Use a GraphQL client or playground (e.g., GraphiQL).
2. Set the endpoint to `https://rickandmortyapi.com/graphql`.
3. Copy and paste the query from the respective `.graphql` file.
4. Execute the query and compare the response with the corresponding `.json` output file.