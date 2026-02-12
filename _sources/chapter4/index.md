(chapter4-main)=
# Working with the SoNAR Interface

````{margin}
```{admonition} Practical
:class: sidebar

**Time:** 10-15 min
```
````

The SoNAR interface has two linked components: a **network graph** (top) and a **data table** (bottom). Filtering the table automatically updates the graph.

```{admonition} Open the SoNAR interface to follow along:
:class: tip

<a href="https://wcrkr3.csb.app/table.html" target="_blank" rel="noopener noreferrer" class="open-app-link">
    <i class="fa-solid fa-external-link-alt"></i> Open SoNAR Interface
</a>
```

```{figure} ../assets/Screenshot.png
---
name: interface-screenshot
---
The SoNAR interface: network graph (top) and filterable data table (bottom)
```

(network-graph)=
## The Network Graph

The graph visualizes correspondence relationships:

- **Nodes** = People (larger nodes have more connections)
- **Edges** = Letters exchanged (thicker lines = more letters)

```{admonition} Hover Interaction
:class: tip

**Hover over a node** to highlight that person (orange), their correspondents (yellow), and fade everyone else (gray).
```

The overlay in the top-left shows the current node/edge count.

(filtering)=
## Filtering the Data

### Text Search (Source/Target columns)

Type in the filter box below the column header. Matching is case-insensitive.

`radecke`

Finds all entries containing "Radecke" in that column.

### Boolean OR Search

Use uppercase **OR** (with spaces) to search multiple terms:

`wagner OR brahms OR liszt`

Finds entries containing any of these names.

```{admonition} Syntax
:class: warning

Must be uppercase **OR** with spaces. Lowercase "or" is treated as literal text.
```

### Date Range (Year Slider)

Drag the slider handles in the Date column header to limit the time period. The graph updates when you release.

(try-it)=
## Try It

| Goal | Action |
| :--- | :--- |
| See one person's network | Type `Radecke` in Target filter |
| Compare multiple figures | Type `wagner OR brahms` in Source filter |
| Focus on 1860s | Set year slider to 1860-1869 |

(export)=
## Exporting Data

Click **"CSV (gefiltert) herunterladen"** to download the currently filtered rows as a CSV file (UTF-8, Excel-compatible).

(chapter4-summary)=
## Summary

```{admonition} Key Points
:class: seealso

- Graph and table are linked-filters update both
- Hover on nodes to explore connections
- Use `OR` for multiple search terms
- Use the year slider for temporal filtering
- Export filtered data as CSV
```
