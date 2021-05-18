# Place context analysis using Natural Language Processing
### :hammer: Exercise
In this exercise, I use Natural Language Processing packages to explore a book Gay Seattle - author's sense of place about Seattle.  I used a parser to parse out the pdf files of the book, then use the NLP packages to do the language analysis.

I then geocode the place names and map them in QGIS. The result is as follows. We can see where people are discussing this issue.
Spatial dimension of sense of place:
![](/assets/06-points.png)

We then use Gephi to map the social connections of those terms.
Social Network analysis:
![](/assets/06-network.png)

Finally, we use word embeddings to generate this graph.
Word Embeddings:
![](/assets/06-snake.png)

Notes: because the `gensim` package has been updated to the most recent version, in the python scripts, we changed `model.wv.vocab` to `model.wv.index_to_key`
Reference: https://stackoverflow.com/questions/66868221/gensim-3-8-0-to-gensim-4-0-0

Reference tutorial can be found here: https://github.com/jakobzhao/geog595/blob/master/06_ai/pe.md.
