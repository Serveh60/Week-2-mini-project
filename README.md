# Week-2-mini-project
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Snippet Cheatsheet</title>
  <link rel="stylesheet" href="assets/css/reset.css" />
  <link rel="stylesheet" href="./assets/css/style.css" />
</head>

<body>


  <header>
    <h1 class="page-title">
      CSS Snippet Cheatsheet
    </h1>
    <p>
      Ever have trouble recalling the exact syntax for your favorite CSS code? Give it a permanent home and add it to
      this page! Select any snippet below and it'll automatically select all of the code for you to copy.
    </p>
  </header>

  <main>
    <section class="row justify-center">
      <div class="card-column">
        <figure class="card code-card">
          <h2 class="card-header">Flexbox Row</h2>
          <div class="card-body">
            <p>Use these three properties to create a Flexbox row layout.</p>
          </div>
          <!-- with the <pre> element, it counts all spaces literally, so proper code indentation cannot be applied in this case -->
          <pre class="code-block"><code>.row {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}</code></pre>
        </figure>
      </div>
      <div class="card-column">
        <figure class="card code-card">
          <h2 class="card-header">Flexbox Column</h2>
          <div class="card-body">
            <p>Use this to create a Flexbox column layout.</p>
          </div>
          <pre class="code-block"><code>.column {
  display: flex;
  flex-direction: column
}</code></pre>
        </figure>
      </div>

      <div class="card-column">
        <figure class="card code-card">
          <h2 class="card-header">CSS Grid Layout</h2>
          <div class="card-body">
            <p>Build a 12-column layout using CSS Grid</p>
          </div>
          <pre class="code-block"><code>.grid {
  display: grid;
  width: 100%;
  grid-template-columns: repeat(12, 1fr);
}</code></pre>
        </figure>
      </div>
      <div class="card-column">
        <figure class="card code-card">
          <h2 class="card-header">Linear Gradients</h2>
          <div class="card-body">
            <p>This will create a background linear gradient from top to bottom.</p>
          </div>
          <pre class="code-block"><code>.linear-gradient-background {
  background-image: linear-gradient(
    rgba(232, 102, 236, 0.3) 0%,
    rgba(232, 102, 236, 0.6) 100%
  );
}</code></pre>
        </figure>
      </div>
      <div class="card-column">
        <figure class="card code-card">
          <h2 class="card-header">Box Transition Glow</h2>
          <div class="card-body">
            <p>Use transition and box shadows to glow on hover.</p>
          </div>
          <pre class="code-block"><code>.code-card .card-header {
  border-radius: 8px;
  transition: all 0.5s ease-in-out;
}

.code-card:hover,
.code-card:hover .card-header {
  box-shadow: inset 0px 0px 8px rgba(232, 102, 236, 1), 0 0 15px rgba(232, 102, 236, 1);
}</code></pre>
        </figure>
      </div>

      <div class="card-column">
        <figure class="card code-card">
          <h2 class="card-header">Overlay Card with Title</h2>
          <div class="card-body">
            <p>Use position properties and negative margins to raise elements higher than their natural starting point.
            </p>
          </div>
          <pre class="code-block"><code>.card-header {
  position: relative;
  margin-top: -20px;
}</code></pre>
        </figure>
      </div>
    </section>
  </main>

  <footer>
    <h3>Made with <span role="img" aria-label="heart">❤️</span> and CSS</h3>
  </footer>

</body>

</html>
