<template>
  <div>
    <Nuxt />
  </div>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #71e0c6;
  color: #71e0c6;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #222;
  background-color: #71e0c6;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 2px solid #6c94be;
  color: #6c94be;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #222;
  background-color: #6c94be;
}
</style>
