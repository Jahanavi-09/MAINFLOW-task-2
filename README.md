# MAINFLOW-task-2
# html code
 <html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>flowers web design</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <header>
    <h1>Hello this is Html</h1>
  </header>

  <nav>
    <ul>
      <li><b><a href="#">Home</a></b></li>
      <li><b><a href="#">About</a></b></li>
      <li><b><a href="#">Services</a></b></li
      <li><b><a href="#">Contact</a></b> </li>
    </ul>
  </nav>

  <main>
    <section>
	<h1> fresh flowers </h1>
      <p><b><button type="button"><a href="https://www.floweraura.com/flowers/bouquet">click here to enter</a></p></b>
    </section>

<section>
      <h2>Our Services</h2>
      <ul>
        <li>Red roses bouquet</li>
        <li>lilly flower buckets</li>
        <li>bellina purple bouquet</li>
      </ul>
    </section>
  </main>
</body>
</html>
# replaced css code
/* Base Styles */
body, h1, h2, p, ul, li {
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.5;
  padding: 0 20px;
}

header {
  background-color: black;
  color: lightgrey;
  text-align: center;
  padding: 20px 0;
}

nav ul {
  list-style: none;
  padding: 10px 0;
  text-align: center;
}

nav ul li {
  display: inline-block;
  margin: 0 10px;
}

nav ul li a {
  color: #333;
  text-decoration: none;
}

main {
  padding: 20px 0;
}

section {
  margin-bottom: 20px;
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 10px 0;
}

/* Media Queries */
@media (min-width: 481px) and (max-width: 768px) {
  nav ul li {
    margin: 0 15px;
  }

  main {
    padding: 15px 0;
  }

  section {
    margin-bottom: 15px;
  }

  footer {
    padding: 8px 0;
  }
}

@media (min-width: 769px) {
  header {
    padding: 25px 0;
  }

  nav ul {
    padding: 10px 0;
  }

  nav ul li {
    margin: 0 20px;
  }

  main {
    padding: 20px 0;
  }

  section {
    margin-bottom: 20px;
  }

  footer {
    padding: 10px 0;
  }
}

/* Small devices (mobile phones) */
@media (max-width: 480px) {
  header {
    padding: 15px 0;
  }

  nav ul li {
    display: block;
    margin: 10px 0;
  }

  main {
    padding: 10px 0;
  }

  section {
    margin-bottom: 10px;
  }

  footer {
    padding: 5px 0;
  }
}

/* Improve Accessibility */
a:focus, a:hover {
  color: #0056b3;
  text-decoration: underline;
}

nav ul li a:focus, nav ul li a:hover {
  color: #0056b3;
  text-decoration: underline;
}
