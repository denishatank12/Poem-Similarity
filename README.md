# Poem-Similarity
 Use this notebookLinks to an external site. as a template and modify as you need to.
Rubric:
Purpose of this segment of the NLP course is to fine tune a model that represents yuor poet.

1. Pick one poet
2. Scrape 30-40 poems from this poet
3. convert the poems into one <poet>_<poem_name>.jsonl
4. Use this notebook to fine tune a mistral 7b model with the 30-40 poems of that poet
5. save the model as <poet>_mistral7b.mod
6. query the model for new poetry
7. your model will generate new poetry in the style of the original poet
8. save the output for 5 poems you generate
9. try [poem] and try [line] determine which one of these chunking options will generate more coherent language

Note: save the output from each prompt so we can evaluate the coherence of the generated language

10. assess the cosine similarity between the generated poems of this poem -- whatever this lang model produces and the previous poems you scraped from this poet.
11. Human assessment of the resulting outcomes
