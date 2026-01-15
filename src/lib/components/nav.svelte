<script lang="ts">
  import { base } from "$app/paths";
</script>

<nav id="nav">
  <ul>
    <li><a href="{base}">Hjem</a></li>
    <li><a href="{base}/about">Om oss</a></li>
  </ul>
</nav>

<style>
#nav {
    position: sticky;
    top: 0;
    left: 0;
    background-color: var(--fg);
    color: var(--bg);
    padding: 0.5rem;
    display: grid;
    grid-template-columns: 1fr;
    align-items: center;

    > ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 3rem;
      margin: 1rem;

      a {
        text-decoration: none;
        color: inherit;
        display: inline-block;
        transition: transform 200ms ease;
        font-size: 2rem;

        &:hover {
          text-decoration: underline;
          transform: scale(1.1);
        }

        &:active {
          transform: scale(1);
        }
      }
    }
  }
</style>
