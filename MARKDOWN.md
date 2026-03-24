# A first-level heading

## A second-level heading

### A third-level heading

#### A four-level heading

##### A five-level heading

###### A six-level heading

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam est odio, commodo id diam sed, pulvinar sagittis tortor. Nam vestibulum purus eros. Sed congue, mi id pretium auctor, nibh augue iaculis arcu, eu tristique quam dolor at erat.

Quisque vel odio condimentum, mollis sem vitae, porta diam. Praesent ligula elit, condimentum eget ex sed, commodo sollicitudin sapien.

Proin volutpat faucibus nulla. Nullam eros sem, ultricies gravida nunc nec, dapibus posuere nisl. Nunc lacinia elementum turpis in pharetra. Aenean eu neque eros.

<!-- This content will not appear in the rendered Markdown -->

**bold**

_italics_

~~strikethrough~~

Comparison text <sub>subscript</sub>

Comparison text <sup> superscript </sup>

> Text that is a quote

## Code Block

### Inline Code Example

JavaScript provides three different value comparison operations: strict equality using `===`, loose equality using `==`, and the `Object.is()` method.

```javascript
// ES5 syntax
var multiply = function (x, y) {
  return x * y;
};

// ES6 arrow function
var multiply = (x, y) => {
  return x * y;
};

// Or even simpler
var multiply = (x, y) => x * y;
```

## Links

A markdown file divides links into two categories: **inline** and **relative**.

#### Inline links

To create an inline link in a Markdown file, wrap the link text in brackets `[ ]` followed immediately by the URL in parentheses `( )`.

This site was built using [GitHub Pages](https://pages.github.com/).

[Contribution guidelines](docs/CONTRIBUTING.md)

![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)

1. one
2. two
3. three
4. four

- First item
- Second item
- Third item
- Fourth item

## Task list

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

Don't forget to leave a star on our repository! :star:

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

| First Header | Second Header |
| ------------ | ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

<details>
  <summary>Click to here. </summary>

### You can add a message here

You can add text within a collapsed section.

You can add an image or a code block, too.

The collapsed syntax looks like this in the browser:

</details>

---

### Creating diagrams

To add diagrams to a Markdown file, use triple backticks and wrap them inside quadruple backticks. Then, tell which identifier (Mermaid, GeoJSON, TopJSON, ASCII STL) you used for the diagram.

GitHub supports diagrams using four syntaxes: mermaid, geoJSON, topoJSON, and ASCII STL.

1. [Mermaid](#heading-mermaid)
2. [GeoJSON and TopoJSON](#heading-geojson-and-topojson)
3. [ASCII STL](#heading-ascii-stl)

#### Mermaid

[Mermaid](https://mermaid.js.org) is a Markdown-inspired tool that renders text into diagrams. You can create flow charts, sequence diagrams, pie charts, and more with Mermaid.

The GitHub-flavored Markdown has extended the functionality of using Mermaid with Markdown.

You can create flow charts, sequence diagrams, pie charts, and so on inside Markdown. GitHub handles the rest of that. So how do you render diagrams on the screen?

```mermaid
graph LR;
   A --  and --> B -- to --> C
```

### ASCII STL

GitHub Flavored Markdown supports STL syntax. STL syntax allows you to add interactive 3D models in markdown. You can use the following syntax: ` ```stl your code.``` `

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
