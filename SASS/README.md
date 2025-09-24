#  Bloom Boutique - Flower Bouquets Website


---

##  SASS Features Used

| Feature        | Description |
|----------------|-------------|
| `$variables`   | For consistent colors, spacing, radius |
| `@mixin`       | For reusable card styles |
| `@include`     | To apply mixins in `.card` |
| Nesting        | Clean and readable component-based CSS |
| Grid Layout    | Responsive card layout using `auto-fit` |

- Install [Node.js](https://nodejs.org/)
- Install SASS globally:
```bash
npm install -g sass

Compile SASS

Inside your project folder, run:

sass styles.scss styles.css


This will convert your .scss file into a browser-readable .css file.

To watch and auto-compile on changes:

sass --watch styles.scss styles.css


