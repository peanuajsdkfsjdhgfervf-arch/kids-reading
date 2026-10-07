# Kids Reading

A small static reading site with shelves for Ruth, Raph, Izzy, and Kids.

The site uses plain HTML and CSS, with no scripts, external fonts, images, or build step. Its shared stylesheet is designed for readable article pages on phones and in reading services such as Instapaper. Plain semantic HTML remains readable when a reader omits the stylesheet.

## Readings

- [The Secret City Beneath the Ice](the-secret-city-beneath-the-ice.html)
- [The Basement World Cup](the-basement-world-cup.html)
- [La Coupe du monde du sous-sol — français](la-coupe-du-monde-du-sous-sol.html)

Both Kids readings contain their complete original text in semantic HTML articles.
The Basement World Cup is also available in French, with links between the two language versions.

## GitHub Pages

Publish from the `main` branch and the `/ (root)` folder in **Settings → Pages**. The `.nojekyll` file lets GitHub Pages serve the HTML and CSS directly.

Home page: https://peanuajsdkfsjdhgfervf-arch.github.io/kids-reading/

## Add a reading

Create an HTML file in the repository root. Include a descriptive page title, one main article heading, and the full text in paragraphs. Link to `styles.css`, and add a link to the reading in the matching section of `index.html`.
