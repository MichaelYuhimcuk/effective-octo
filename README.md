<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Simple Website</title>
  <style>
 * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
  }
  
  header {
    background-color: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
  }
  
  header h1 {
    margin-bottom: 0.5rem;
  }
  
  nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 1rem;
  }
  
  nav a {
    color: #fff;
    text-decoration: none;
  }
  
  nav a:hover {
    text-decoration: underline;
  }
  
  main {
    padding: 2rem;
    background-color: #fff;
    max-width: 800px;
    margin: 2rem auto;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  
  footer {
    text-align: center;
    padding: 1rem;
    background-color: #333;
    color: #fff;
  }

  </style>
  </head>
<body>
  <header>
    <h1>Welcome to My Website</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>About This Site</h2>
      <p>This is a simple website made with HTML and CSS. You can customize it to suit your needs.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 My Website</p>
  </footer>
</body>
</html>
