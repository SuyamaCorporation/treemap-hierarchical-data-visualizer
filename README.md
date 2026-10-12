## Treemap Hierarchical Data Visualizer

An interactive treemap using the Squarified Treemap algorithm implemented entirely in vanilla JS and SVG. Three built-in datasets are included (world population, file system mock, budget categories). Cells are color-coded by top-level category and display percentage labels.

**Tech:** Vanilla JS, inline SVG, Tailwind CSS. **How to use:** Select a dataset from the dropdown, then click any cell with children to drill down into that subtree. Use the breadcrumb trail to navigate back up. Hover any cell for a tooltip showing name, value, and percentage of parent. Paste custom JSON in the format `[{"name":"A","value":100,"children":[...]}]` to visualize your own hierarchical data.
