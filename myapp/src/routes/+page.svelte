<script>
  import { Arrow, Card } from "$lib/index.js";
</script>

<section>
  <p class="label">Label</p>
  <h1>Mandatory title <br> about <span>the call-to-action</span> here</h1>
  <p class="body-copy">Optional body copy goes here.</p>
  <a href="/">Optional button <Arrow /></a>
</section>

<ul>
  <li><Card /></li>
  <li><Card /></li>
</ul>

<style>
  section {
    display: grid;
    justify-items: center;
    gap: 16px;
    margin-bottom: 32px;
    max-width: 864px;
    margin-inline: auto;
    text-align: center;
  }

  p {
    font-weight: 450;
  }

  .label {
    color: #39494D;
    font-size: 14px;
    line-height: 16px;
    letter-spacing: 0.02em;
  }

  h1 {
    font-weight: 575;
    font-size: 36px;
    line-height: 40px;
    color: #212121;
    letter-spacing: -0.02em;
  }

  h1 span {
    font-family: 'GT Alpina';
    font-weight: 300;
    font-size: 38px;
    letter-spacing: -0.03em;
  }

  .body-copy {
    color: #4B5050;
    font-size: 17px;
    line-height: 24px;
  }

  a {
    display: inline-flex;
    align-items: center;
    gap: 4px;
    font-weight: 450;
    font-size: 17px;
    line-height: 24px;
    color: #BF564D;
    text-decoration: none;
  }

  a svg {
    padding: 5px;
  }

  a path {
    stroke: currentColor;
  }

  a:hover {
    color: rgb(166, 67, 58);
  }

  ul {
    list-style: none;
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-inline: auto;
    padding: 0;
  }

  li {
    flex: 1 1 335px;
  }

  @media only screen and (min-width: 768px) {
    section {
      margin-bottom: 48px;
      gap: 24px;
    }

    .label {
      font-size: 15px;
    }

    h1 {
      font-size: 40px;
      line-height: 48px;
      letter-spacing: -0.03em;
    }

    h1 span {
      font-size: 42px;
    }

    .body-copy {
      font-size: 19px;
    }

    a {
      font-size: 19px;
    }
  }

  @media only screen and (min-width: 1440px) {
    section {
      margin-bottom: 80px;
    }

    ul {
      gap: 24px;
    }
  }
</style>
