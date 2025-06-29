# Rick and Morty GraphQL Query

This project contains a GraphQL query that fetches details of characters from the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql).

## 📌 Objective

Use the `charactersByIds` GraphQL query to retrieve information about characters with IDs 1, 2, 3, and 4.

## 🧠 Query Details

The following fields are fetched for each character:
- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

## 🔎 Sample Query (inside `getCharacters.graphql`)

```graphql
query GetCharacters {
  charactersByIds(ids: [1, 2, 3, 4]) {
    id
    name
    status
    species
    type
    gender
  }
}
