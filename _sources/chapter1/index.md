(chapter1-main)=
# What is Historical Network Analysis?

````{margin}
```{admonition} Quick Read
:class: sidebar

**Time:** 10-15 min
```
````

**Historical Network Analysis (HNA)** applies network science to historical data. Instead of studying individuals in isolation, it examines the **relationships** between people-who knew whom, who corresponded with whom, who collaborated or competed.

(definition)=
## Definition

```{admonition} What is HNA?
:class: note

HNA represents historical actors as **nodes** and their relationships as **edges**. This allows researchers to visualize, measure, and analyze patterns of connection in the past.
```

HNA emerged from two fields:

- **Social Network Analysis (SNA)** - Methods for studying social structures
- **Digital Humanities** - Computational tools for historical sources

(key-concepts)=
## Key Concepts

### Basic Elements

| Concept | Meaning | Example |
| :--- | :--- | :--- |
| **Node** (Vertex) | An entity in the network | A person: "Brahms, Johannes (1833-1897)" |
| **Edge** (Link) | A connection between two nodes | A correspondence relationship between two people |
| **Directed Edge** | Connection with direction (A?B) | Brahms wrote *to* Clara Schumann |
| **Undirected Edge** | Connection without direction (A-B) | Brahms and Clara corresponded (either direction) |
| **Weight** | Strength or frequency of connection | 50 letters exchanged = weight of 50 |

### Network Structures

| Concept | Meaning | Example |
| :--- | :--- | :--- |
| **Degree** | Number of connections a node has | Brahms corresponded with 50 people = degree of 50 |
| **Cluster** | Group of densely connected nodes | The "Brahms circle" of close allies |
| **Component** | A connected subnetwork | All people reachable from Brahms through correspondence |
| **Path** | Route between two nodes via edges | Brahms ? Joachim ? Liszt (path length = 2) |
| **Density** | Proportion of possible connections that exist | High density = many people correspond with each other |

(centrality)=
## Centrality Measures

**Centrality** measures how important a node is in the network. Different measures capture different types of importance:

| Measure | What it measures | Example |
| :--- | :--- | :--- |
| **Degree Centrality** | Number of direct connections | Clara Schumann corresponded with 200 people ? high degree centrality. She was a **hub**. |
| **Betweenness Centrality** | How often a node lies on shortest paths between others | Liszt connected the Brahms and Wagner camps ? high betweenness. He was a **broker**. |
| **Closeness Centrality** | Average distance to all other nodes | Someone who can reach everyone in few steps ? high closeness. They hear news **quickly**. |
| **Eigenvector Centrality** | Connections to well-connected people | Knowing a few famous composers matters more than knowing many unknown ones ? **quality over quantity**. |

```{admonition} Key Insight
:class: tip

A person can be important in different ways. Someone with low degree but high betweenness is a crucial **bridge** between groups, even if they don't have many contacts overall.
```

(why-networks)=
## Why Think in Networks?

Networks reveal patterns invisible in traditional research:

- **Ideas spread** through connections between people
- **Factions form** as like-minded people cluster together
- **Brokers matter** - some individuals bridge separate groups
- **Position explains power** - who you know affects what you can do

(applications)=
## Applications

HNA has been used to study:

| | |
| :--- | :--- |
| **Republic of Letters** | Correspondence networks of Enlightenment scholars (Voltaire, Locke, etc.) |
| **Renaissance Florence** | How the Medici rose to power through their unique broker position |
| **Trade networks** | Commercial connections between merchants and cities |
| **Musical networks** | Correspondence among 19th-century composers (this course!) |

(limitations)=
## Limitations

```{admonition} Important Caveats
:class: warning

Historical network data differs from modern social network data. Keep these limitations in mind:
```

| Limitation | Explanation |
| :--- | :--- |
| **Incomplete data** | Many letters were lost, destroyed, or never archived. We see only what survived. |
| **Survival bias** | Famous people's letters were more likely to be preserved than those of lesser-known figures. |
| **Missing edge problem** | No documented correspondence does not mean no relationship. People may have met in person or used other means. |
| **Edge meaning ambiguity** | An edge shows correspondence existed, but not whether it was friendly, hostile, or purely formal. |
| **Temporal gaps** | Some periods are better documented than others. Patterns may reflect archival survival, not actual activity. |
| **Quantification limits** | Network metrics are precise numbers, but their historical meaning requires careful interpretation. |

```{admonition} Best Practice
:class: note

Always combine network analysis with traditional historical methods. Use networks to generate hypotheses and identify patterns, but validate findings through close reading and contextual knowledge.
```

(chapter1-summary)=
## Summary

```{admonition} Key Points
:class: seealso

- HNA studies **relationships**, not just individuals
- Core elements: **nodes** (people) and **edges** (connections)
- Key structures: degree, clusters, components, paths
- Centrality measures: degree, betweenness, closeness, eigenvector
- Historical data is always incomplete-interpret with caution
```
