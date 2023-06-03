# HTML_Task4
# HTML File Links

This README file provides instructions on how to create HTML file links to navigate between different pages within a website.

## Link Structure

To create a link to an HTML file, you can use the `<a>` element with the `href` attribute. Here's an example of how to create a link to another HTML file:

```html
  <a href="#">Go to another Page</a>
```

In the above example, the `href` attribute specifies the path to the target HTML file. In this case, the link will take the user to "page2.html" when clicked.

## Absolute and Relative Paths

When specifying the path in the `href` attribute, you can use either absolute or relative paths.

- **Absolute Path**: This specifies the complete URL or file path from the root of the website. For example:

  ```html
  <a href="https://example.com/page2.html">Go to Page 2</a>
  ```

- **Relative Path**: This specifies the path relative to the current HTML file. For example:

  ```html
  <a href="pages/page2.html">Go to Page 2</a>
  ```

  In this case, the "page2.html" file is located in a folder called "pages" within the same directory as the current HTML file.

## Usage

To create HTML file links in your website, follow these steps:

1. Create a new HTML file or open an existing one in a text editor.
2. Identify the target HTML file you want to link to and determine the appropriate path (absolute or relative).
3. Use the `<a>` element with the `href` attribute to create the link. For example:

   ```html
   <a href="#">Go to another Page</a>
   ```

4. Customize the link text according to your preference. In the example above, the link text is "Go to Page 2".
5. Repeat the process to create additional links to other HTML files if needed.
6. Save the HTML file.
7. Open the HTML file in a web browser to test the links. Clicking on the links should navigate to the corresponding HTML files.

That's it! You have now created HTML file links to navigate between different pages within your website.
