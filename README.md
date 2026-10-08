# Kids Reading

A small static reading site with shelves for Ruth, Raph, Izzy, and Kids.

The site uses plain HTML and CSS, with no scripts, external fonts, or build step. The illustrated stories use local PNG images shared between their English and French versions. Its shared stylesheet is designed for readable article pages on phones and in reading services such as Instapaper. Plain semantic HTML remains readable when a reader omits the stylesheet.

## Readings

- [Ruth and the Invisible Starting Line](ruth-and-the-invisible-starting-line.html)
- [Ruth et la ligne de départ invisible — français](ruth-et-la-ligne-de-depart-invisible.html)
- [Raph and the Unbeatable Team](raph-and-the-unbeatable-team.html)
- [Raph et l'équipe imbattable — français](raph-et-l-equipe-imbattable.html)
- [Izzy and the Bus-Stop Face-Off](izzy-and-the-bus-stop-face-off.html)
- [Izzy et la mise au jeu à l'arrêt d'autobus — français](izzy-et-la-mise-au-jeu-a-l-arret-d-autobus.html)
- [The Secret City Beneath the Ice](the-secret-city-beneath-the-ice.html)
- [The Basement World Cup](the-basement-world-cup.html)
- [The Basement World Cup - Illustrated](the-basement-world-cup-illustrated.html)
- [La Coupe du monde du sous-sol — français](la-coupe-du-monde-du-sous-sol.html)
- [La Coupe du monde du sous-sol - Illustrated — français](la-coupe-du-monde-du-sous-sol-illustrated.html)

Both Kids readings contain their complete original text in semantic HTML articles.
The Basement World Cup is also available in French, with links between the two language versions. Separate Illustrated editions preserve the full story text and add an opening scene, a course map, a scoreboard, and the asteroid-saving finale. Both languages share the same black-and-white artwork with localized image descriptions. The original text editions remain available.

The Ruth, Raph, and Izzy shelves each have a short illustrated introduction in English and French, with two scenes of the children interacting. Ruth is thirteen and loves track and field; Raph is twelve and loves soccer; Izzy is ten and loves hockey. The language versions link to each other, and each page links to the other introductions. Raph's historical World Cup scores have FIFA source links in the footer, outside the story.

## GitHub Pages

Publish from the `main` branch and the `/ (root)` folder in **Settings → Pages**. The `.nojekyll` file lets GitHub Pages serve the HTML, CSS, and image assets directly.

Home page: https://peanuajsdkfsjdhgfervf-arch.github.io/kids-reading/

## Add a reading

Create an HTML file in the repository root. Include a descriptive page title, one main article heading, and the full text in paragraphs. Link to `styles.css`, and add a link to the reading in the matching section of `index.html`.
