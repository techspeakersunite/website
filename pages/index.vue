<template>
  <div class="page-wrapper">
    <div>
      <Logo />
      <p class="subtitle">
        A place where tech speakers gather to share experiences and resources in
        order to foster a strong and healthy community.
      </p>
      <div class="links">
        <a
          href="https://github.com/techspeakersunite"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Github
        </a>
        <a
          href="https://twitter.com/techspeakersuni"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          Twitter
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.page-wrapper {
  margin: 0 auto;
  width: 100%;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background-color: #101010;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 500;
  font-size: 1.2rem;
  color: #ccc;
  word-spacing: 5px;
  padding-bottom: 15px;
  max-width: 50ch;
  margin: 0 auto 1rem;
}

@media (min-width: 768px) {
  .subtitle {
    font-size: 1.5rem;
    max-width: 70ch;
  }
}

.links {
  padding-top: 15px;
}
</style>
