<script lang="ts">
	import Logo from "./lib/Logo.svelte";
	// export let name: string;
</script>

<main>
	<Logo />
	<p class="intro">
		If you want to deliver outstanding web experiences, we can help you.<br
		/>
		We want the web to be delightful, open and immediate.
	</p>

  <section>
    <h2>Our values</h2>

    <dl>
        <dt>
            Delightful
        </dt>
        <dd>
            The web should be a beautiful place with room for experimentation.
            We meticously convert your beautiful pixel-perfect mockups to interactive live code with exciting animations and transitions. Create an experience instead of a functional tool. 
        </dd>
    </dl>

    <dl>
        <dt>
            Open
        </dt>
        <dd>
            The culture of the web is open & inclusive. We love opensource technologies, and firmly believe in high accessibility. Your experience should be accessible to everyone: from slow connections to handicaps.
        </dd>
    </dl>

    <dl>
        <dt>
            Immediate
        </dt>
        <dd>
            The web is often perceived as a slow platform. But it shouldn't. The web doesn't require you to install apps. Pageloads can be nearly instantanious. Animations can be buttery-smooth. All it takes is a bit of optimization. Noone should wait to enjoy the experience you made. 
        </dd>
    </dl>
  </section>

  <section class="case-studies">
    <h2>Case studies</h2>
    <div class="case-study">
      KBC: (2016): 
    </div>
    <div class="case-study">
      Medialaan (2015): Medialaan
    </div>
  </section>
</main>

<style>
	main {
    font-size: 1.4rem;
    line-height: 1.6;
	}

  section {
    margin: 0 1.6rem 0 3.2rem;
    margin: 0 0 0 1.6rem;
  }

  dd {
    margin: 0;
  }

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
