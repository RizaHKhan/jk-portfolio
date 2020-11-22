<template>
  <div class="landing">
    <div class="title-container">
      <h1 class="title">Jay Khan</h1>
      <p>UI/UX Developer</p>
    </div>
  </div>
</template>

<style lang="scss">
.landing {
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  .title-container {
    @media (min-width: 600px) {
      position: absolute;
      right: 20%;

      .title {
        font-size: 5rem;
      }
      p {
        font-size: 1rem;
      }
    }
    .title {
      font-size: 4rem;
      font-weight: 400;
    }
    p {
      text-align: right;
    }
  }
}
</style>
