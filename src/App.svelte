<script>
  import svelteLogo from './assets/svelte.svg'
</script>

<main>

  <img src="https://cdn-icons-png.flaticon.com/512/4923/4923785.png" class="hero-image" alt="hero-image">

  <div class="logo-container">
    <a href="/"> 
      <img src={svelteLogo} class="logo svelte" alt="Svelte Logo" />
    </a>
  </div>

  <h2>Oops, this page doesn't exist!</h2>
  <p>You visited a link that is not valid. Please return to the homepage.</p>

  <button>Home</button>

</main>

<style>

  .hero-image {
    height: 16em;
    animation: float 4s ease-in  infinite;
  }

  @keyframes float {
  0% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-12px);
  }
  100% {
    transform: translateY(0);
  }
}

  .logo-container {
    position: absolute;
    top: 0;
    left: 2em;
  }

  .logo {
    height: 3.5em;
    padding: 1em;
  }
</style>
