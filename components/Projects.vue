<template>
  <div class="projects">
    <h1>Projects</h1>
    <div class="cards">
      <div class="card">
        <h1 class="title">Project 1</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facere,
          cumque?
        </p>
      </div>
      <div class="card">
        <h1 class="title">Project 1</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facere,
          cumque?
        </p>
      </div>
      <div class="card">
        <h1 class="title">Project 1</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facere,
          cumque?
        </p>
      </div>
      <div class="card">
        <h1 class="title">Project 1</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facere,
          cumque?
        </p>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
.projects {
  padding: 2rem;

  .cards {
    display: grid;
    grid-gap: 10px;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));

    .card {
      border: solid 1px black;
      border-radius: 5px;
    }
  }
}
</style>
