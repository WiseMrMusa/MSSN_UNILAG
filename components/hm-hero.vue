<template>
  <section class="hero-section">
    <div class="left-hero">
      <h1>An association that cares for your need</h1>
      <p>
        Human makes a society. There is no us without you and that’s what makes your need
        our utmost concern.
      </p>
      <button class="pry-btn">Join our members’ list</button>
    </div>
    <div class="right-hero">
      <img src="~/assets/imgs/mos.svg" alt="" />
    </div>
  </section>
</template>

<style>
section.hero-section {
  padding: 50px;
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  height: calc(100vh - 100px);
  align-items: center;
}

h1 {
  margin: 0;
  font-family: Archivo;
  font-size: 60px;
  font-weight: 700;
  letter-spacing: -1.2px;
  max-width: 50rem;
}

p {
  margin: 0;
  font-family: Inter;
}

.left-hero {
  grid-column-start: 1;
  grid-column-end: 6;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  row-gap: 47px;
}

.right-hero {
  grid-column-start: 7;
  grid-column-end: 13;
}

button {
  padding: 20px 40px;
  border-radius: 8px;
  width: fit-content;
  border: none;
}

.pry-btn {
  background-color: #49c4a2;
  color: white;
}
</style>
