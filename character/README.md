# Character Queries

This directory contains GraphQL queries and their corresponding JSON outputs for fetching character data from the Rick and Morty API.

## API Endpoint

- **URL:** [https://rickandmortyapi.com/graphql](https://rickandmortyapi.com/graphql)

## Tasks Covered

### Task 0: Get a Specific Character by ID

Queries designed to retrieve details for specific characters using their unique IDs.

- **Fields included:** `id`, `name`, `status`, `species`, `type`, `gender`
- **Files:** `character-id-[1-4].graphql` and `character-id-[1-4]-output.json`

### Task 1: Get a List of All Characters

Queries designed to retrieve a paginated list of characters.

- **Fields included:** `id`, `name`, `status`, `image`
- **Arguments:** `page` (1, 2, 3, 4)
- **Files:** `characters-page-[1-4].graphql` and `characters-page-[1-4]-output.json`

## How to use

The `.graphql` files contain the raw query text, and the `.json` files contain the data returned by the API when the query is executed.
