# HTML Text mining for YOGA
<button onclick="window.location.href='https://aibialab.github.io/';">**HOME**</button>

HTML-TM Yoga is related to the article of [Ieger Raittz, *et al.*, 2022](https://doi.org/10.1101/2022.12.05.22282979) 


We've provided two HTML's:
1. [Texts](https://aibialab.github.io/HTMLTMYoga/TEXTS.html) - each line corresponds to an article
2. [Words](https://aibialab.github.io/HTMLTMYoga/WORDS.html) - each line corresponds to a term (sort by term id)
3. [Words](https://aibialab.github.io/HTMLTMYoga/WORDS2.html) - each line corresponds to a term (sort by tree order - tree created using the 'complete' algorithm)
4. [Tree](https://aibialab.github.io/HTMLTMYoga/WRDtree.html) - phylogenetic tree of 1500 words (HTML of tree produced with [Phy2HTML])(https://github.com/msrosenberg/Phy2HTML)

Aditional material at the [**link**](https://sourceforge.net/projects/yoga-paper-material/).

## How to use the HTMLs?

#### TEXTS
[TEXTS](https://aibialab.github.io/HTMLTMYoga/TEXTS.html) contains a list of all the articles analysed, as shown in the
image below. Each article has a link to a list of articles (titles+abstract) that most closely match
the query article.

#### WORDS
[WORDS_id](https://aibialab.github.io/HTMLTMYoga/WORDS.html) and [WORDS_tree](https://aibialab.github.io/HTMLTMYoga/WORDS2.html) contains: 1) Cod: word id , 2) WORD: the query term,
3) Related words: a list of the 10 closest words, 3) Link title: a link to the articles (title+abstract)
most related to the term, 4) link abstracts: a link to the tree of terms rooted in the query term, and
5) link graphic: a graph of the frequency of the term in the literature.

The trees are all rooted in the query term. The graph has two curves, one in blue with the
frequency of the term yoga in the literature against time, and in purple the frequency that the query
term is found.

#### TREE
[TREE](https://aibialab.github.io/HTMLTMYoga/WRDtree.html) presents a phylogenetic tree of 1,500 words. The number before the word (label of branch) corresponds to the word id.


## Citation

Please cite this study as follows:

Ieger Raittz, R., De Pierri, C. R., Perico, C. P., Machado, D. J., Marchaukoski, J. N., & Raittz, R. T. (2022). What are we learning with Yoga: a text mining approach to literature. medRxiv, 2022-12. <https://doi.org/10.1101/2022.12.05.22282979>

