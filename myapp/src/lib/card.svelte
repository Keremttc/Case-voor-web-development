<script>
  import { Arrow } from "$lib/index.js";
</script>

<a href="/" aria-label="Lees meer over de call-to-action">
  <article>
    <header>
      <h2>Title</h2>
      <p>Supporting text about the call-to-action goes here.</p>
    </header>
    <span class="button">
      <Arrow />
    </span>
  </article>
</a>

<style>
  a {
    text-decoration: none;
    display: block;
  }

  article {
    position: relative;
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    min-width: 335px;
    min-height: 257px;
    border-radius: 4px;
    background-color: #ffdfb2;
    background-image:
      linear-gradient(rgba(218, 0, 0, 0), rgb(20, 20, 20)),
      url(/images/image-1.png);
    background-position: center;
    background-size: cover;
    padding: 24px 16px;
  }

  header {
    display: grid;
    gap: 8px;
    width: 80%;
    color: white;
    z-index: 1;
  }

  h2 {
    font-weight: 600;
    font-size: 22px;
    line-height: 24px;
    letter-spacing: -0.01em;
    color: #ffffff;
    margin: 0;
  }

  p {
    font-weight: 450;
    font-size: 17px;
    line-height: 24px;
    color: #fafafa94;
    margin: 0;
  }

  .button {
    width: 48px;
    height: 48px;
    border-radius: 4px;
    border: 2px solid rgba(255, 255, 255, 0.812);
    background-color: transparent;
    cursor: pointer;
    display: flex;
    justify-content: center;
    align-items: center;
    color: #ffffff;
    z-index: 1;
    flex-shrink: 0;
  }

  .button svg {
    width: 14px;
    height: 14px;
  }

  .button path {
    stroke: #ffffff;
  }

  a:hover .button {
    border: 2px solid #ffffff76;
  }

  @media only screen and (min-width: 768px) {
    article {
      height: 45vh;
      padding: 32px 24px;

    }

    h2 {
      font-size: 28px;
      line-height: 32px;
      letter-spacing: -0.02em;
    }

    p {
      font-size: 19px;
    }
  }

  @media only screen and (min-width: 1440px) {
    article {
      width: 644px;
      height: 515px;
    }
  }
</style>
