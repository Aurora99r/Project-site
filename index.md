---

 ALL ABOUT ARCO CLOTHES
---
Welcome to our website, we are Laura, Alena, Aurora and Juliana. This project is part of an academic assessment for the "Information and Technology Skills" course in the Master's program "Language, Society, and Communication" at the University of Bologna. 

It focuses on analyzing and using knowledge graphs from ARCO and Large Language Models. The selected ARCO ontology was about clothing description. The main goal of using this ontology is to explore clothing characteristics and compare LLMS with the better option to enrich the knowledge graph.

In the following parts you will have information about the methodology, results and analysis, discussion, conclusion and possible future developments.

## Methodology
The tools used for developing this project were: 
GITHUB (Image- logo) (Links)
SPARQL (Image- logo) (Links)
ARCO (Image- logo) (Links)
CHAT GPT (Image- logo) (Links)
GEMINI (Image- logo) (Links)
LLAMA (Image- logo) (Links)
Class material (Image- logo) (Links)


### Prompting techniques
The LLMS used were: CHAT GPT, LLAMA,  GEMINI.
The prompting techniques used were Zero-shot Prompting, Few-Shot Prompting, Chain-of-thought, and Generated-knowledge-prompting. To enrich the knowledge graph we asked the following questions:
Enhance the "a-cd:subject" Relationship
Cultural Property: Cappotto, maschile – Novità Confezioni Italiane Eleganza (XX secolo)
Owner: Damiano Chiesa
What are the craftsmanship techniques used in the 'Cappotto, maschile – Novità Confezioni Italiane Eleganza'?
Take into account that Craftsmanship is the skill that someone uses when they make beautiful things with their hands. 
Can you extract exactly what the main topics are based on this answer? 
Could you transform this description into RDF format? Explain the process for getting this RDF format. 
Could you use the ArCo clothing ontology? 

The first question corresponds to the few-shot prompting since it provides context on what is a Craftsmanship so the LLM can give more specialized information about it. 
<img width="1440" alt="1" src="https://github.com/Aurora99r/Project-site/assets/169910091/c55363e5-4df3-46f8-bccf-e222580895b7">

#### Header 4
SPARQL QUERIES
There are any military uniforms in the clothing description ontology?
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX arco: <https://w3id.org/arco/ontology/arco/>
PREFIX a-cd: <https://w3id.org/arco/ontology/clothing-description/>
PREFIX agent: <https://w3id.org/arco/resource/Agent/>
SELECT *
WHERE {
?Clothing
rdfs:label ?label 
FILTER(REGEX(?label, "uniforme, militare"))
}
LIMIT 3


*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Our Report

1.  Julia Tapia
2.  Aurora Arnone
3.  Laura Podaru
4.  Alena Vulf

Methodology: github, SPARQL, ARCO, CHAT GPT, Challenges
SPARQL Dati cultura
-
Pros:


Cons:
* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


Data Sources

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
