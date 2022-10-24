These are *opinonated* snippets I find useful in the construction of Shopify projects.

They may or may not be useful to you. My intention behind the extension is to use it as
a learning excercise, and also to make them project-agnostic.

All subject to change - and I change my mind frequently.

Ideally, the snippet files should follow this format also - Snippets that have large affects, down to smaller.
(Scaffold -> Component -> Wrap -> Tag).

Points to note -
- What's the best way to handle tabs / spaces.

## Snippet terminology

All snippets are lowercase, hyphenated between words.
They are prefixed by their function.

| Command | Example | Description
| :------------- | :------------- | :------------- |
| `scaffold-` | `scaffold-section` | Scaffolds a 'section' or 'snippet'.
| `component-` | `component-section` | Adds the HTML structure for a component, such as as 'section' or a 'table'.
| `wrap-` | `wrap-if` | Surrounds the highlighted code. For example an 'if' statement.
| `tag-` | `tag-liquid` | (Liquid only) Boilerplated tags. For example, `{% liquid %}`.

## Updating the extension

| Command | Description
| :------------- | :------------- |
| `vsce publish minor` | Publishes a minor update version.