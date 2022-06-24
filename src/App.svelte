<script>
  import './lib/style/global.css';
</script>

<main>
  <h1>Women's Strike</h1>
  <h2>We have to save ourselves.</h2>
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans',
      'Helvetica Neue', sans-serif;
  }

  main {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100%;
  }

  img {
    height: 16rem;
    width: 16rem;
  }

  h1,
  h2 {
    color: #ffffff;
    text-transform: uppercase;
    font-weight: bolder;
    line-height: 1.1;
    margin: 2rem auto;
    letter-spacing: 0.025em;
  }

  h1 {
    font-size: 3rem;
    max-width: 14rem;
  }

  p {
    max-width: 14rem;
    margin: 1rem auto;
    line-height: 1.35;
    color: #ffffff;
    text-transform: uppercase;
  }

  @media (min-width: 480px) {
    h1 {
      max-width: none;
      font-size: 5rem;
    }

    p {
      max-width: none;
    }
  }
</style>
