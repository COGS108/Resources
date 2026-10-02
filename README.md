# COGS 108 Resources

Helpful resources for students in COGS 108: Data Science in Practice at UC San Diego.

Nothing here is required. Use it to review something from lecture, get unstuck on your
project, or go deeper than the course has time for. Sections after the fundamentals follow
the same order as the course itself.

Every entry has a one-line description and a tag for what kind of thing it is:
*book*, *video*, *interactive*, *course*, *docs*, *cheat sheet*, *data*, *paper*, *tool*.

**Found a dead link, or something that helped you that isn't here?**
Open an issue or a pull request — see [Contributing](#contributing).

---

## Contents

**Fundamentals**
- [Python](#python)
- [Practicing Python](#practicing-python)
- [Jupyter Notebooks](#jupyter-notebooks)
- [git and GitHub](#git-and-github)

**Following the course**
- [Finding and Collecting Data](#finding-and-collecting-data)
- [SQL and Databases](#sql-and-databases)
- [Data Ethics and Privacy](#data-ethics-and-privacy)
- [Data Wrangling with pandas](#data-wrangling-with-pandas)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Visualization](#data-visualization)
- [Statistics and Inference](#statistics-and-inference)
- [Text Analysis and NLP](#text-analysis-and-nlp)
- [Machine Learning](#machine-learning)
- [Geospatial Data](#geospatial-data)
- [Communicating Results](#communicating-results)

**Reference**
- [Cheat Sheets](#cheat-sheets)
- [Troubleshooting](#troubleshooting)
- [Getting Help](#getting-help)
- [Contributing](#contributing)

---

## Python

COGS 108 assumes you already know basic Python. If you're rusty, start here.

- [Introduction to Python](https://shanellis.github.io/pythonbook) — the COGS 18 textbook, written for this course sequence; the fastest way to review exactly the Python COGS 108 expects. *(book)*
- [COGS 18 course site](https://cogs18.github.io/) — lecture slides and materials from the prerequisite course. *(course)*
- [COGS 18 Materials repo](https://github.com/COGS18/Materials) — notebooks and practice problems from COGS 18. *(course)*
- [The Python Tutorial](https://docs.python.org/3/tutorial/) — the official language tutorial; the authoritative answer to "how does this actually work?" *(docs)*
- [Python Crash Course, 3rd ed. resources](https://ehmatthes.github.io/pcc_3e/) — free cheat sheets, solutions, and setup guides from a popular intro book (the book itself is paid). *(book, cheat sheet)*

## Practicing Python

Reading about Python isn't the same as writing it. These give you problems to solve.

- [Practice Python](https://www.practicepython.org/) — short beginner exercises with solutions; good for a 15-minute warm-up. *(interactive)*
- [CodingBat: Python](https://codingbat.com/python) — bite-sized logic and string/list problems that check your answer instantly. *(interactive)*
- [Codecademy: Learn Python 3](https://www.codecademy.com/learn/learn-python-3) — guided in-browser course, no install required (some content requires a paid account). *(course)*
- [Exercism: Python track](https://exercism.org/tracks/python) — 140+ exercises with automated feedback and free human mentoring. *(interactive)*
- [LeetCode](https://leetcode.com/) — interview-style algorithm problems; harder and more algorithm-focused than anything COGS 108 requires, but useful if you're prepping for internships. *(interactive)*

## Jupyter Notebooks

- [Jupyter documentation](https://docs.jupyter.org/en/latest/) — official docs for notebooks and JupyterLab, including keyboard shortcuts and the interface tour. *(docs)*
- [Markdown Basic Syntax](https://www.markdownguide.org/basic-syntax/) — how to format the markdown cells in your notebook (headers, links, lists, code blocks). *(docs)*

## git and GitHub

### Guides and tutorials

- [GitHub Docs: Hello World](https://docs.github.com/en/get-started/using-github/hello-world) — official 15-minute walkthrough of repos, branches, commits, and pull requests. *(docs)*
- [GitHub Docs: Getting started](https://docs.github.com/en/get-started) — the umbrella guide; where to look when you need the official answer. *(docs)*
- [git — the simple guide](https://rogerdudler.github.io/git-guide/) — one page covering the handful of commands you'll actually use. *(docs)*
- [Learn Git Branching](https://learngitbranching.js.org/) — interactive visual sandbox; the clearest way to build a mental model of branches and merges. *(interactive)*
- [GitHub Desktop docs](https://docs.github.com/en/desktop) — official docs for the point-and-click app, if you'd rather avoid the command line. *(docs)*
- [Managing personal access tokens](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens) — GitHub no longer accepts your password over HTTPS; this is how you generate the token you use instead. *(docs)*
- [COGS 108 GitHub Cheat Sheet](https://docs.google.com/document/d/1mgjHQWkQaSQcdGSZHYKYUU9z8dMI1268V9zzNMcxO5k/edit?tab=t.0) - summary of content discussed in lecture

### Video walkthroughs from COGS 108 staff

- [Installing and using `git`, Part 1](https://www.youtube.com/watch?v=ng4X6qF8XVY) — install `git`, clone a repo, and make your first commits from the command line, by TA Ganesh. *(video, 22 min)*
- [Merge conflicts and branching, Part 2](https://youtu.be/Nk1gtrbTZ2Y) — what a merge conflict is and how to resolve one, by IA Shubham Kulkarni. *(video, 8 min)*
- [Using `git` with GitHub Desktop](https://youtu.be/zQc5vQEBips) — the same workflow without the terminal, by TA Sidharth Suresh. *(video, 13 min)*
- [Git & GitHub Tutorial](https://www.youtube.com/watch?v=xuB1Id2Wxak) — longer end-to-end tutorial from edureka!, with [companion notes](https://docs.google.com/document/d/1GAdkvn7lWzeLekvC343WNZC2rZGhQOfPOU2dMha9aws/edit) by TA Holly (Yueying Dong). *(video)*
- [Personal Access Token tutorial](https://docs.google.com/document/d/1Sb6tQwUVBhzcmBGWw4UnhGlYcMDdyUy3gaRKcQzYur4/edit?usp=sharing) — step-by-step token setup with screenshots, by Scott Yang. *(docs)*

### When git goes wrong

- [Dangit, Git!?!](https://dangitgit.com/) — plain-English fixes for the most common "I've broken my repo" situations. *(docs)*
- See also [Troubleshooting](#troubleshooting) below for notebooks too large to push.

## Finding and Collecting Data

### Where to find data for your project

- [UCSD Library: Data & Statistics Sources](https://ucsd.libguides.com/data-statistics) — the librarians' guide to datasets, including ones UCSD pays for so you don't have to; start here. *(data)*
- [San Diego & California data](https://ucsd.libguides.com/data-statistics/sandiego) — regional data sources, useful for projects about campus or the city. *(data)*
- [City of San Diego Open Data Portal](https://data.sandiego.gov/) — 120+ machine-readable city datasets (311 requests, police calls, permits, budgets), updated daily. *(data)*
- [Kaggle Datasets](https://www.kaggle.com/datasets) — tens of thousands of user-uploaded datasets; convenient, but check the provenance before you build a project on one. *(data)*
- [Google Dataset Search](https://datasetsearch.research.google.com/) — search engine for datasets published anywhere on the web. *(data)*
- [Data.gov](https://data.gov/) — the U.S. federal government's open data catalog. *(data)*
- [data.census.gov](https://data.census.gov/) — U.S. Census and American Community Survey tables; the standard source for demographic context. *(data)*
- [FiveThirtyEight data](https://github.com/fivethirtyeight/data) — the cleaned datasets behind their published stories, each with a README explaining the columns. *(data)*
- [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) — large community-curated list of open datasets by topic. *(data)*

### Collecting data yourself

- [`requests` documentation](https://requests.readthedocs.io/en/latest/) — the standard library for pulling data from web APIs. *(docs)*
- [Beautiful Soup documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) — parsing HTML when the data you need is only on a web page. *(docs)*

> **Before you scrape:** check the site's terms of service and `robots.txt`, rate-limit your
> requests, and prefer an official API when one exists. See
> [Data Ethics and Privacy](#data-ethics-and-privacy).

## SQL and Databases

- [SQLBolt](https://sqlbolt.com/) — 18 interactive in-browser lessons from `SELECT` to joins; the quickest way to get productive. *(interactive)*
- [SQL Tutorial](https://www.thoughtspot.com/sql-tutorial) — analyst-oriented tutorial with real data, organized around questions rather than syntax (formerly the Mode Analytics tutorial). *(interactive)*
- [PostgreSQL Exercises](https://pgexercises.com/) — graded practice problems against a sample database, from basics to window functions. *(interactive)*

## Data Ethics and Privacy

- [Data Feminism](https://data-feminism.mitpress.mit.edu/) — how power shapes what gets counted and by whom; the full book is free online. *(book)*
- [Datasheets for Datasets](https://arxiv.org/abs/1803.09010) — Gebru et al. on documenting a dataset's collection, composition, and intended uses; a useful checklist for your own project. *(paper)*
- [Gender Shades](https://proceedings.mlr.press/v81/buolamwini18a.html) — Buolamwini & Gebru's audit showing how aggregate accuracy hides large disparities across subgroups. *(paper)*

## Data Wrangling with pandas

- [Getting started with pandas](https://pandas.pydata.org/docs/getting_started/index.html) — the official tutorials, organized by task ("how do I select a subset?"). *(docs)*
- [10 minutes to pandas](https://pandas.pydata.org/docs/user_guide/10min.html) — whirlwind tour of the API; good for a quick refresher. *(docs)*
- [Kaggle: Learn pandas](https://www.kaggle.com/learn/pandas) — hands-on interactive lessons in your browser, with exercises. *(interactive)*
- [Python for Data Analysis, 3rd ed.](https://wesmckinney.com/book/) — the definitive pandas book, by the author of pandas; free to read online. *(book)*
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) — NumPy, pandas, matplotlib, and scikit-learn in one free book, written as notebooks. *(book)*
- [Tidy Data](https://vita.had.co.nz/papers/tidy-data.pdf) — Wickham's paper on why one-row-per-observation makes everything downstream easier. *(paper)*

## Exploratory Data Analysis

- [Exploratory Data Analysis chapter, *R for Data Science*](https://r4ds.hadley.nz/eda) — the questions to ask of a new dataset; the code is R, but the thinking transfers directly. *(book)*
- [Missing data in pandas](https://pandas.pydata.org/docs/user_guide/missing_data.html) — how pandas represents missing values and what your options are for handling them. *(docs)*

## Data Visualization

- [From Data to Viz](https://www.data-to-viz.com/) — decision tree from your data type to an appropriate chart, with code and common pitfalls. *(interactive)*
- [The Python Graph Gallery](https://python-graph-gallery.com/) — hundreds of charts with copy-pasteable code, organized by chart type. *(docs)*
- [Fundamentals of Data Visualization](https://clauswilke.com/dataviz/) — Wilke's free book on why some charts work and others mislead; light on code, heavy on judgment. *(book)*
- [seaborn tutorial](https://seaborn.pydata.org/tutorial.html) — official tutorial for the library that makes statistical plots short to write. *(docs)*
- [matplotlib cheat sheets](https://matplotlib.org/cheatsheets/) — one-page references for the plotting API and styling. *(cheat sheet)*

## Statistics and Inference

- [Seeing Theory](https://seeing-theory.brown.edu/) — interactive visual introduction to probability, distributions, inference, and regression. *(interactive)*
- [Think Stats, 3rd ed.](https://allendowney.github.io/ThinkStats/) — Downey's free book teaching statistics through Python code rather than formulas. *(book)*
- [StatQuest](https://www.youtube.com/@statquest) — short, clear videos on individual statistics and ML concepts; excellent when one idea from lecture didn't land. *(video)*
- [`scipy.stats` reference](https://docs.scipy.org/doc/scipy/reference/stats.html) — the statistical tests and distributions available in Python, with usage notes. *(docs)*

## Text Analysis and NLP

- [NLP in Python](https://www.youtube.com/watch?v=xvqsFTUsOmc) — conference-talk walkthrough of a text analysis project end to end, from raw text to findings. *(video)*
- [spaCy 101](https://spacy.io/usage/spacy-101) — gentle introduction to tokenization, part-of-speech tagging, and named entities using a modern NLP library. *(docs)*
- [Text feature extraction in scikit-learn](https://scikit-learn.org/stable/modules/feature_extraction.html#text-feature-extraction) — how to turn documents into the bag-of-words and TF-IDF matrices models expect. *(docs)*
- [Natural Language Processing with Python](https://www.nltk.org/book/) — the free NLTK book; thorough on linguistic fundamentals. *(book)*

## Machine Learning

- [Kaggle: Intro to Machine Learning](https://www.kaggle.com/learn/intro-to-machine-learning) — build and validate your first model in a few hours, in the browser. *(interactive)*
- [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html) — the reference for every model you're likely to use, with worked examples and guidance on choosing one. *(docs)*
- [Machine Learning, Andrew Ng](https://www.youtube.com/watch?v=PPLop4L2eGk&list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN) — the classic full-length lecture series on the math behind common algorithms. *(video, course)*
- [MIT Intro to Deep Learning](http://introtodeeplearning.com/) — MIT's short course, with lecture videos and labs; refreshed each year. *(course)*
- [TensorFlow and Keras course](https://www.youtube.com/watch?v=tPYj3fFJGjk) — long-form free course on building neural networks, well past what COGS 108 covers. *(video, course)*
- [From 0 to Research Scientist](https://github.com/ahmedbahaaeldin/From-0-to-Research-Scientist-resources-guide) — a structured reading path through ML, DL, RL, and NLP if you want to go much deeper. *(course)*

## Geospatial Data

- [GeoPandas: Introduction](https://geopandas.org/en/stable/getting_started/introduction.html) — working with geographic data in a DataFrame; start here. *(docs)*
- [GeoPandas: Mapping and plotting](https://geopandas.org/en/stable/docs/user_guide/mapping.html) — making choropleths and other maps from a GeoDataFrame. *(docs)*
- [GeoPandas: Set operations with overlay](https://geopandas.org/en/stable/docs/user_guide/set_operations.html) — intersecting, clipping, and combining spatial layers. *(docs)*
- [GeoPandas: Example gallery](https://geopandas.org/en/stable/gallery/index.html) — worked examples to adapt for your own maps. *(docs)*

## Communicating Results

- [Fundamentals of Data Visualization: Telling a story](https://clauswilke.com/dataviz/telling-a-story.html) — structuring a set of figures into an argument a reader can follow. *(book)*
- [How to ask a good question](https://stackoverflow.com/help/minimal-reproducible-example) — how to build a minimal reproducible example; makes the answers you get on the course forum far more useful. *(docs)*

## Cheat Sheets

- [pandas cheat sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf) — one-page PDF of the most common DataFrame operations. *(cheat sheet)*
- [matplotlib cheat sheets](https://matplotlib.org/cheatsheets/) — plotting and styling at a glance. *(cheat sheet)*
- [Python Crash Course cheat sheets](https://ehmatthes.github.io/pcc_3e/cheat_sheets/) — one-pagers for core Python syntax, lists, dicts, and classes. *(cheat sheet)*

## Troubleshooting

**My notebook is too big to push to GitHub.**
Large images and plots stored in notebook output can push a file past GitHub's size limit.
Clear the outputs before committing:

```bash
jupyter nbconvert --clear-output --inplace MyNotebook.ipynb
```

If you need to keep the outputs, [`ipynbcompress`](https://pypi.org/project/ipynbcompress/)
shrinks the embedded images instead. *(tool)*

**I have a merge conflict.**
See [Merge conflicts and branching](https://youtu.be/Nk1gtrbTZ2Y) *(video, 8 min)* and
[Dangit, Git!?!](https://dangitgit.com/).

**GitHub is rejecting my password.**
GitHub requires a personal access token for HTTPS, not your account password. See
[Managing personal access tokens](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens).

## Getting Help

Course logistics, assignments, and deadlines live on the course website and Canvas, not here.
For questions about the material, post on the course forum — and include a
[minimal reproducible example](https://stackoverflow.com/help/minimal-reproducible-example)
so staff can actually see what went wrong.

## Contributing

This list is maintained by COGS 108 staff and students. If a link is dead, a description is
wrong, or you found something that helped you:

1. Open an issue describing the change, **or**
2. Open a pull request editing this README directly.

When adding a resource, please match the existing format — a link, an em dash, one line on
what it is and when it's useful, and a tag:

```markdown
- [Title](https://example.com) — what it is and when you'd reach for it. *(tag)*
```
