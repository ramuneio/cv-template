<script>
  export let role;
</script>

<style>
  h3,
  h4 {
    margin: 0;
    padding: 0;
    font-size: 1em;
    font-weight: 500;
  }

  .project {
    margin: calc(var(--margin) / 2) 0 0 0;
  }

  header {
    margin-bottom: calc(var(--margin) / 2);
    display: grid;
    grid-template-columns: 1fr max-content;
  }

  label {
    white-space: nowrap;
  }

  .tools {
    display: flex;
  }

  ul {
    padding: 0 0 0 1.5em;
    margin: 0;
    list-style: disc;
  }
</style>

<li class="project">
  <header>
    <h3>{role}</h3>
    <slot class="tools" name="tools" />
  </header>
  <ul>
    <slot />
  </ul>
</li>
