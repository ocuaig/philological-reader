# Philological Reader
A simple interface for reading texts with links to dictinoaries.

## How to use locally
1. Clone this repository or download the three files `index.html`, `reader.js`, `style.css` to the same folder.
2. Open `index.htm` in a web brower.

## How to adapt dictionaries
1. Open `reader.js`.
2. Add, edit or remove dictionaries within the `dictionary` variable at the top.
3. Each dictionary entry within `{ }` brackets contains an `id`, `label` and `url`. If your dictionary has entries with addresses like `https://www.dictionary.com/something/sample-headword`, then you can add a dynamic link as follows: 
`https://www.dictionary.com/something/${word}`