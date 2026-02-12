(chapter5-main)=
# Research Applications

````{margin}
```{admonition} Applied
:class: sidebar

**Time:** 10 min
```
````

Now that you know how to use the SoNAR interface, this chapter shows how to apply these skills to historical research questions.

(research-questions)=
## Example Research Questions

Network analysis can help answer questions like:

| Question Type | Example |
| :--- | :--- |
| **Central figures** | Who had the most correspondents in the 1860s? |
| **Connections** | Did Johannes Brahms and Richard Wagner share any mutual contacts? |
| **Temporal change** | How did correspondence patterns change after 1883 (Wagner's death)? |
| **Hidden figures** | Which lesser-known people connected major composers? |
| **Network structure** | Are there distinct clusters (Brahms camp vs. Wagner camp)? |

(case-study)=
## Mini Case Study

```{admonition} Finding Brokers Between Camps
:class: tip

**Question:** Who corresponded with both the Brahms circle and the Wagner circle?

1. In Source filter, type: `brahms OR joachim OR hanslick`
2. Note the correspondents shown in the graph
3. Clear filter, then type: `wagner OR liszt OR b&uuml;low`
4. Look for names that appear in both results
5. These are potential "brokers" who bridged both camps
```

```{admonition} Interpretation
:class: tip

Finding someone in both networks does not prove they were a mediator-it is a starting point for further historical investigation.
```

(going-further)=
## Going Further

For more advanced analysis, export your filtered data and use specialized tools:

| Tool | Use Case |
| :--- | :--- |
| [Gephi](https://gephi.org/) | Advanced visualization, centrality metrics, community detection |
| [NetworkX](https://networkx.org/) (Python) | Programmatic analysis, custom algorithms |
| [igraph](https://igraph.org/r/) (R) | Statistical network analysis, modeling, community detection, and graph metrics in R |
| [Palladio](https://hdlab.stanford.edu/palladio/) | Humanities-focused visualization (no coding) |

```{admonition} Export Workflow
:class: note

Filter your data in SoNAR &rarr; Download CSV &rarr; Import into Gephi or other tools for deeper analysis.
```

(your-turn)=
## Your Turn

Try formulating your own research question and use SoNAR to explore it:

1. Define a question (who, what, when)
2. Choose appropriate filters (names, date range)
3. Examine the graph for patterns
4. Export data if needed for further analysis
5. Interpret findings in historical context

```{admonition} Remember
:class: warning

Network data shows *documented* correspondence. Absence of an edge does not mean two people never communicated-only that no letter survives in this collection.
```

(chapter5-summary)=
## Summary

```{admonition} Key Points
:class: seealso

- Network analysis reveals patterns invisible in traditional research
- Start with a clear question, then choose filters
- Findings are starting points, not conclusions
- Export data for advanced analysis in Gephi or similar tools
```
