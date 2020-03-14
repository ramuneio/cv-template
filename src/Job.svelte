<script>
  export let client;
  export let when;
  export let where;
</script>

<style>
  .job {
    display: grid;
    margin-bottom: calc(var(--margin) * 2);
  }

  header {
    display: flex;
  }

  h1 {
    font-size: 1em;
    padding: 0;
    margin: 0;
    color: var(--text-colour);
    font-weight: 500;
  }

  .projects {
    list-style: none;
    margin: 0;
    padding: 0;
  }

  b {
    flex: 1;
  }
</style>

<div class="job">
  <header>
    <h1>{client}, {where}</h1>
    <b />
    <h1>{when}</h1>
  </header>
  <ul class="projects">
    <slot />
  </ul>
</div>
