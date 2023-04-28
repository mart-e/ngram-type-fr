# Extraction and Transformation of French n-grams

This section contains the code used to extract French n-grams.

The source data `1gramstop10k.csv` was obtained from https://github.com/orgtre/frenchngrams,
which is a frequency table of the most common french words,
"built from the top 400 most popular French books on Project Gutenberg (as of 2016-12-04)"

I then used chatGPT to create a `extract.py` and `transform.py` script
to perform the data wrangling. The initial prompts are included
in the scripts. Note that this code may not be optimal
at all, but it does the job.