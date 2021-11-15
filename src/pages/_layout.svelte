<!-- routify:options preload="proximity" -->
<!-- <nav> is for nav bar -->
<nav>
	<code>Provided by src/pages/_layouts.svelte:</code>
	<a href="/"> Home </a>
	<a href="/about"> About </a>
	<a href="/portfolio"> Portfolio </a>
</nav>
<!-- <slot /> is for page content -->
<main>
	<slot />
</main>

<style>
  nav {
    background-color: pink;
    position: fixed;
    height: 30px;
    width: 100%;
  }
  main {
    padding-top: 30px;
    margin: 0;
  }
  :global(body) {
    padding: 0;
  }
</style>