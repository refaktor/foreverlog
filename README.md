# forever-log

Apps come and go, only text is forever

## Reasoning

Write your text in markdown. You can always read it, render it, index it and structure it as graph.

Forever-log brings you graph, search and scripting. You bring the files.

Forever files are where your projects are.

FL is local-first, linux-first and console-first.

## What forever-log is not

* it's not a editor, you bring your own
* it's not a location, you store files where you work

## What forever-log is 

### v0.01

A graph: a superstructure of projects, documents, tasks, goals

A CLI utilities to: 

* add folder
* remove remove
* to commit
* to explore graph 

### v0.02

A full text search.

A CLI utility to:

* search graph

## Implementation

forever-log is written in Rye. It uses cayley with boltdb for embedded graph database and bleve for full text search.
