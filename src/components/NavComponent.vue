<template>
  <div class="nav-component">
    <div class="link-wrapper">
      <a href="">Home</a>
      <a href="">Portfolio</a>
      <a href="">About</a>
      <a href="">Contact</a>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style>
.nav-component {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  width: 100vw;
  height: 5vh;
  background-color: var(--color-background-nav);
  padding: 5px;
}

.link-wrapper {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  width: 25%;
  margin-left: 75%;
  margin-right: 1%;
}

.link-wrapper h1 {
  color: var(--font-color-light);
  font-weight: bold;
}

.link-wrapper a{
  text-decoration: none;
  transition: 0.25s ease-in-out;
  font-size: 1.25rem;
  color: white;
  text-shadow: 3px 3px 10px black;
  padding:5px;
}

@media (hover: hover) {
  .link-wrapper a:hover {
    transform: scale(1.155);
  }
}
</style>
