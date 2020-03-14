<script>
  export let className = "";
  export let tag;
</script>

<style>
  :root {
    --k8s: 219, 76%, 55%;
    --elastic: 169, 64%, 69%;
    --react: 193, 100%, 68%;
    --graphql: 319, 100%, 44%;
    --sketch: 25, 87%, 51%;
    --css: 0, 0%, 90%;
    --elixir: 310, 85%, 26%;
    --axure: 330, 83%, 80%;
    --electron: 191, 56%, 70%;
    --vue: 154, 48%, 49%;
    --firebase: 45, 100%, 58%;
    --svg: 0, 0%, 75%;
    --angularjs: 347, 100%, 80%;
    --bootstrap: 264, 34%, 36%;
    --csharp: 268, 53%, 37%;
    --wpf: 268, 53%, 67%;
    --java: 0, 100%, 40%;
    --python: 46, 77%, 37%;
    --solaris: 0, 0%, 0%;
    --unix: 192, 100%, 25%;
    --postgres: 207, 78%, 38%;
    --kafka: 193, 85%, 29%;
    --redis: 4, 74%, 49%;
  }

  label {
    border-radius: 20px;
    padding: 1px 6px;
  }

  .tag {
    color: white;
  }

  .node {
    color: #2f4f4f;
    background-color: hsla(var(--vue), 0.4);
  }

  .k8s {
    color: #00008b;
    background-color: hsla(var(--k8s), 0.5);
  }

  .elastic {
    color: #007070;
    background-color: hsla(var(--elastic), 0.5);
  }

  .react {
    color: #007070;
    background-color: hsla(var(--react), 0.5);
  }

  .graphql {
    color: #800080;
    background-color: hsla(var(--graphql), 0.3);
  }

  .css {
    color: #008080;
    background-color: hsla(var(--css));
  }

  .elixir {
    background-color: hsla(var(--elixir), 0.6);
  }

  .axure {
    color: #006400;
    background-color: hsla(var(--axure), 0.4);
  }

  .electron {
    color: #006400;
    background-color: hsla(var(--electron), 0.8);
  }

  .sketch {
    color: #8b0000;
    background-color: hsla(var(--sketch), 0.5);
  }

  .vue {
    background-color: hsla(var(--vue), 0.85);
  }

  .aws,
  .firebase {
    color: #cc7000;
    background-color: hsla(var(--firebase), 0.4);
  }

  .svg {
    background-color: hsla(var(--svg));
  }

  .angularjs {
    color: #4c0640;
    background-color: hsla(var(--angularjs));
  }

  .bootstrap {
    color: #663399;
    background-color: hsla(var(--bootstrap), 0.3);
  }

  .csharp {
    background-color: hsla(var(--bootstrap), 0.7);
  }

  .wpf {
    background-color: hsla(var(--wpf));
  }

  .unix {
    background-color: hsla(var(--unix), 0.6);
  }

  .java {
    background-color: hsla(var(--java), 0.55);
  }

  .python {
    color: #6a5acd;
    background-color: hsla(var(--firebase), 0.5);
  }

  .solaris {
    background-color: hsla(var(--solaris), 0.35);
  }

  .oracle {
    color: #800080;
    background-color: hsla(var(--angularjs), 0.3);
  }

  .cplusplus {
    background-color: hsla(var(--k8s), 0.7);
  }

  .ida {
    color: #483d8b;
    background-color: hsla(var(--postgres), 0.2);
  }

  .postgres {
    background-color: hsla(var(--postgres), 0.75);
  }

  .kafka {
    background-color: hsla(var(--kafka), 0.7);
  }

  .redis {
    background-color: hsla(var(--redis), 0.7);
  }
</style>

<label class={`tag ${tag} ${className}`}>{tag}</label>
