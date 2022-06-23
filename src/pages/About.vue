<template>
  <div class="container">
  <h2> Favorites</h2>
    <RecipePreviewList
      v-if="this.clicked"
      title="Favorites"
      state="favorites"
      class="RandomRecipes center"
    />
  </div>
</template>