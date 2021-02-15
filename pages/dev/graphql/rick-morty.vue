<template>
  <div>
    Rick & Morty GraphQL API
    <h1>
      <div>
        <ul>
          <li
            v-for="character in characters.results"
            :key="characters.id"
            class="my-3"
          >
            <div class="flex">
              <div class="w-1/2">
                <h1 class="text-2xl font-semibold">{{ character.name }}</h1>
                <p>{{ character.status }}</p>
              </div>
              <div>
                <div class="h-16 w-16 bg-gray-900 rounded-full"></div>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </h1>
  </div>
</template>

<script>
import gql from "graphql-tag";
export default {
  apollo: {
    characters: gql`
      query getCharacters {
        characters {
          results {
            id
            name
            status
          }
        }
      }
    `
  }
};
</script>
