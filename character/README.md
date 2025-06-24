# GraphQL Character Data Queries

This repository contains GraphQL queries to retrieve specific character information based on their ID from a GraphQL API.

## Objective

Write GraphQL queries to fetch details of characters with IDs 1, 2, 3, and 4, including the following fields:
- id
- name
- status
- species
- type
- gender

## Files

- `character-id-1.graphql`  
- `character-id-1-output.json`  
- `character-id-2.graphql`  
- `character-id-2-output.json`  
- `character-id-3.graphql`  
- `character-id-3-output.json`  
- `character-id-4.graphql`  
- `character-id-4-output.json`  

Each `.graphql` file contains the query for the corresponding character ID. The `.json` files contain the expected response from the API.

## How to Use

1. Review and customize the `.graphql` files if needed.
2. Run the queries against your GraphQL API endpoint.
3. Save the actual responses in the respective `-output.json` files.

## Example Query

```graphql  
query {  
  character(id: 1) {  
    id  
    name  
    status  
    species  
    type  
    gender  
  }  
}  