<script>
  import Header from "./Header.svelte";
  import Job from "./Job.svelte";
  import Project from "./Project.svelte";
  import ToolTag from "./ToolTag.svelte";
  import ProjectContent from "./ProjectContent.svelte";
</script>

<style>
  :root {
    --text-colour: #656565;
    --margin: 1em;
    --margin-half: calc(var(--margin) / 2);
    --margin-2x: calc(var(--margin) * 2);
  }

  p {
    margin: 0;
  }

  main {
  }

  .page-body {
    display: grid;
    grid-template-columns: 6fr 2.5fr;
    grid-column-gap: calc(var(--margin) * 4);
  }

  .content-section {
    display: grid;
    grid-template-rows: min-content 1fr;
    margin: 0 0 var(--margin-2x) 0;
  }

  .section-header {
    font-size: 1.25em;
    margin: 0 0 var(--margin-half) 0;
  }

  .skill-block {
    margin: var(--margin-half) 0;
  }

  .skill-block.first {
    margin-top: 0;
  }
</style>

<main>

  <Header />
  <div class="page-body">
    <div>
      <div class="content-section">
        <header class="section-header">Selected Experience</header>

        <Job client="Frozen Banana Stand" where="The OC" when="2006">
          <Project role="Mr Manager">
            <span slot="tools">
              <ToolTag tag="css" />
              <ToolTag tag="python" />
              <ToolTag tag="vue" />
              <ToolTag tag="aws" />

              <ToolTag tag="react" />
              <ToolTag tag="redis" />
            </span>
            <li>There's always money in the banana stand</li>
            <li>I've made a huge mistake</li>
            <li>I make a meal for my friends</li>
            <li>Try to make it delicious</li>
            <li>Try to keep it nutritious</li>
            <li>Create wonderful dishes</li>
            <li>Not one of them thinks about the way I feel</li>
            <li>Nobody compliments the meal</li>
          </Project>
        </Job>

        <Job client="Gothic Castle" where="Wee Brain" when="2007">
          <Project role="Leather Daddy">
            <span slot="tools">
              <ToolTag tag="k8s" />
              <ToolTag tag="node" />
              <ToolTag tag="elixir" />
              <ToolTag tag="elastic" />
              <ToolTag tag="graphql" />
            </span>
            <li>Baby, you've got a stew going!</li>
            <li>You're gonna get some hop-ons.</li>
            <li>He doesn't cook or clean</li>
            <li>Is that the kind of thing that you think you might be into?</li>
          </Project>
        </Job>

        <Job client="Frozen Banana Stand" where="The OC" when="2006">
          <Project role="Mr Manager">
            <span slot="tools">
              <ToolTag tag="css" />
              <ToolTag tag="python" />
              <ToolTag tag="vue" />
              <ToolTag tag="aws" />

              <ToolTag tag="react" />
              <ToolTag tag="redis" />
            </span>
            <li>There's always money in the banana stand</li>
            <li>I've made a huge mistake</li>
            <li>I make a meal for my friends</li>
            <li>Try to make it delicious</li>
            <li>Try to keep it nutritious</li>
            <li>Create wonderful dishes</li>
            <li>Not one of them thinks about the way I feel</li>
            <li>Nobody compliments the meal</li>
          </Project>
        </Job>

        <Job client="Gothic Castle" where="Wee Brain" when="2007">
          <Project role="Leather Daddy">
            <span slot="tools">
              <ToolTag tag="k8s" />
              <ToolTag tag="node" />
              <ToolTag tag="elixir" />
              <ToolTag tag="elastic" />
              <ToolTag tag="graphql" />
            </span>
            <li>Baby, you've got a stew going!</li>
            <li>You're gonna get some hop-ons.</li>
            <li>He doesn't cook or clean</li>
            <li>Is that the kind of thing that you think you might be into?</li>
          </Project>
        </Job>

        <Job client="Frozen Banana Stand" where="The OC" when="2006">
          <Project role="Mr Manager">
            <span slot="tools">
              <ToolTag tag="css" />
              <ToolTag tag="python" />
              <ToolTag tag="vue" />
              <ToolTag tag="aws" />

              <ToolTag tag="react" />
              <ToolTag tag="redis" />
            </span>
            <li>There's always money in the banana stand</li>
            <li>I've made a huge mistake</li>
            <li>I make a meal for my friends</li>
            <li>Try to make it delicious</li>
            <li>Try to keep it nutritious</li>
            <li>Create wonderful dishes</li>
            <li>Not one of them thinks about the way I feel</li>
            <li>Nobody compliments the meal</li>
          </Project>
        </Job>

        <Job client="Gothic Castle" where="Wee Brain" when="2007">
          <Project role="Leather Daddy">
            <span slot="tools">
              <ToolTag tag="k8s" />
              <ToolTag tag="node" />
              <ToolTag tag="elixir" />
              <ToolTag tag="elastic" />
              <ToolTag tag="graphql" />
            </span>
            <li>Baby, you've got a stew going!</li>
            <li>You're gonna get some hop-ons.</li>
            <li>He doesn't cook or clean</li>
            <li>Is that the kind of thing that you think you might be into?</li>
          </Project>
        </Job>

        <Job client="Frozen Banana Stand" where="The OC" when="2006">
          <Project role="Mr Manager">
            <span slot="tools">
              <ToolTag tag="css" />
              <ToolTag tag="python" />
              <ToolTag tag="vue" />
              <ToolTag tag="aws" />

              <ToolTag tag="react" />
              <ToolTag tag="redis" />
            </span>
            <li>There's always money in the banana stand</li>
            <li>I've made a huge mistake</li>
            <li>I make a meal for my friends</li>
            <li>Try to make it delicious</li>
            <li>Try to keep it nutritious</li>
            <li>Create wonderful dishes</li>
            <li>Not one of them thinks about the way I feel</li>
            <li>Nobody compliments the meal</li>
          </Project>
        </Job>

        <Job client="Gothic Castle" where="Wee Brain" when="2007">
          <Project role="Leather Daddy">
            <span slot="tools">
              <ToolTag tag="k8s" />
              <ToolTag tag="node" />
              <ToolTag tag="elixir" />
              <ToolTag tag="elastic" />
              <ToolTag tag="graphql" />
            </span>
            <li>Baby, you've got a stew going!</li>
            <li>You're gonna get some hop-ons.</li>
            <li>He doesn't cook or clean</li>
            <li>Is that the kind of thing that you think you might be into?</li>
          </Project>
        </Job>

      </div>
    </div>

    <div class="column">
      <div class="content-section">
        <header class="section-header">About Me</header>
        <p>
          Jan met another man Liza got amnesia, just forgot who I am Felicity
          said there was no electricity Emily, no chemistry Fran, ran, Bruce
          turned out to be a man Flo had to go, I couldn't go with the flow
          Carol Brown just took the bus out of town But I'm hoping that you'll
          stick around.
        </p>
      </div>
      <div class="content-section">
        <header class="section-header">Education</header>
        <div class="skill-block" style="margin-top: 0">
          <small>UNIVERSITY OF DARTLINGBORNE, UK</small>
          <p>Maths or something, I did my best.</p>
        </div>

      </div>

      <div class="content-section">
        <header class="section-header">Key Skills</header>

        <div class="skill-block first">
          <small>SKILL SECTION 1</small>
          <p>Cooking hot ham water, being blue</p>
        </div>

        <div class="skill-block">
          <small>SKILL SECTION 2</small>
          <p>Cooking hot ham water, being blue</p>
        </div>

        <div class="skill-block">
          <small>OTHER</small>
          <p>Sandwiches</p>
        </div>

      </div>

      <div class="content-section">
        <header class="section-header">Languages</header>

        <div class="skill-block first">
          <small>ENGLISH (UK)</small>
          <p>Native</p>
        </div>
        <div class="skill-block first">
          <small>English (US)</small>
          <p>Beginner</p>
        </div>
      </div>

      <div class="content-section">
        <header class="section-header">Contact</header>
        <div class="skill-block" style="margin-top: 0">
          <p>tobias@bluemangroup.com</p>
        </div>
        <div class="skill-block" style="margin-top: 0">
          <p>091 889 99383</p>
        </div>
        <div class="skill-block" style="margin-top: 0">
          <p>https://github.com/ramuneio/cv-template</p>
        </div>
      </div>

    </div>
  </div>

</main>
