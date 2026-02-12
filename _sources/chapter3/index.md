(chapter3-main)=
# The SoNAR Data Marketplace

````{margin}
```{admonition} Quick Read
:class: sidebar

**Time:** 5 min
```
````

The SoNAR data marketplace contains correspondence entries from the [Kalliope Union Catalog](https://kalliope-verbund.info/), specifically from the music department of the Berlin State Library (Staatsbibliothek zu Berlin, Musikabteilung). The data was exported in **Dublin Core format** and transformed for network analysis.

(data-structure)=
## Data Structure

Each entry has five columns:

| Column | Description |
| :--- | :--- |
| **Source** | Sender (Name, life dates) |
| **Target** | Recipient (Name, life dates) |
| **Type** | Relationship direction (Undirected) |
| **Label** | Relationship type (hasCorrespondent) |
| **Date** | Date of letter (YYYY-MM-DD) |

(sample-data)=
## Sample Data

| Source | Target | Type | Label | Date |
| :--- | :--- | :--- | :--- | :--- |
| Kienzl, Wilhelm (1857-1941) | Radecke, Robert (1830-1911) | Undirected | hasCorrespondent | 1887-11-11 |
| Scraback, Reinhold | Radecke, Robert (1830-1911) | Undirected | hasCorrespondent | 1906-07-18 |
| Scraback, Reinhold | Radecke, Robert (1830-1911) | Undirected | hasCorrespondent | 1906-07-28 |
| Kieslich, Leo (1882-1956) | Radecke, Robert (1830-1911) | Undirected | hasCorrespondent | 1911-05-25 |
| Kiessling, Thekla | Radecke, Robert (1830-1911) | Undirected | hasCorrespondent | 1859-12-14 |
| Kinkeldey, Otto (1878-1966) | Radecke, Robert (1830-1911) | Undirected | hasCorrespondent | 1909-11-27 |
| Seckendorff, Curt von (1846-1895) | Radecke, Robert (1830-1911) | Undirected | hasCorrespondent | 1873-03-13 |
| Seebach, Marie (1829-1897) | Radecke, Robert (1830-1911) | Undirected | hasCorrespondent | 1881-11-11 |

```{admonition} Note
:class: note

The same person pair can appear multiple times with different dates (e.g., Scraback & Radecke above). Life dates are sometimes missing when unknown.
```

(interface)=
## Two Views

SoNAR provides two linked views:

- **Graph** - Visual network (nodes = people, edges = letters)
- **Table** - Filterable data with text search and date slider

Filtering the table automatically updates the graph.

(chapter3-summary)=
## Summary

```{admonition} Key Points
:class: seealso

- Data sourced from Kalliope (Berlin State Library, Music Department)
- Original format: Dublin Core
- 5 columns: Source, Target, Type, Label, Date
- Graph + Table views, linked by filters
```
