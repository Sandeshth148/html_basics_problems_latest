# HTML Document Structure

An HTML document is divided into two main parts:

## 1. `<head>` Section

The `<head>` contains metadata and links to external resources. It does not render visible content on the webpage.

### Common Elements in `<head>`:

```html
<head>
  <meta charset="UTF-8" />
  <!-- Defines character encoding -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <!-- Responsive design support -->
  <title>My HTML Page</title>
  <!-- Page title shown in the browser tab -->
  <meta name="description" content="A brief description of the page." />
  <meta name="keywords" content="HTML, CSS, JavaScript" />
  <meta name="author" content="Your Name" />

  <link rel="stylesheet" href="styles.css" />
  <!-- Link to external CSS -->
  <script src="script.js" defer></script>
  <!-- Link to external JS -->
</head>
```

2. <body> Section
   The <body> contains all the visible content that appears on the webpage.

Common Elements in <body>:

```
<body>
    <header>
        <h1>Welcome to My Page</h1> <!-- Main heading -->
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
            <h2>About Us</h2>
            <p>This section contains information about our website.</p>
        </section>

        <article>
            <h2>Latest News</h2>
            <p>Stay updated with our latest blog posts and announcements.</p>
        </article>
    </main>

    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>
</body>
```

# Can HTML Be Nested Inside HTML?

## ❌ Invalid but Renders in Browsers

Even though **nesting `<html>` inside another `<html>` is invalid**, browsers **attempt to correct it** and still render the content.

### Example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Outer HTML</title>
  </head>
  <body>
    <h1>Main Page</h1>

    <html>
      <head>
        <title>Inner HTML</title>
      </head>
      <body>
        <h2>Nested HTML</h2>
        <p>This shouldn't work, but browsers try to render it.</p>
      </body>
    </html>

    <p>Back to the main document.</p>
  </body>
</html>
```
