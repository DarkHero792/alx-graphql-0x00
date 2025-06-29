# Character GraphQL Queries

This directory contains GraphQL queries and their results for characters from the Rick and Morty API.

## Endpoint
- https://rickandmortyapi.com/graphql

## Fetched Characters
Each character was fetched using the `character(id: ID!)` field, requesting the following fields:
- id
- name
- status
- species
- type
- gender

## Files
| ID | Query File | Output File |
|----|------------|-------------|
| 1  | character-id-1.graphql | character-id-1-output.json |
| 2  | character-id-2.graphql | character-id-2-output.json |
| 3  | character-id-3.graphql | character-id-3-output.json |
| 4  | character-id-4.graphql | character-id-4-output.json |
