# TextSimilarity

## Introduction
This is a text analysis project where data is collected from Wikipedia before being analyzed to detect similarities.

## Execution
1. First of all, I crawl data about members of the Cabinet of Australia from the Wikipedia page: https://en.wikipedia.org/wiki/Cabinet_of_Australia to get the text description corresponding to each of the member.

2. All adjectives in the text description are then filtered out to be studied using `Spacy`.

3. The text descriptions are then encoded using `SBERT`.

4. Pairwise cosine similarity was then calculated for all of the descriptions using `Sklearn`. Pairs with similarity score greater than 0.8 are then filtered out to be studied.
