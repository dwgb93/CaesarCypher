# CaesarCypher
This was an old project I created when I was learning Python.

A friend asked me if I could create a Caesar Cypher solver (easy) that automatically produced a likely-correct cleartext, without having to scroll through 26 other cyphers.

Given the distribution of letters in the language (assumed to be English), I thought that the dot product of the English language distribution with all 26 possible cypher text distributions would be largest when the ``vectors'' were most aligned. Obviously, this wouldn't work well with very short or deliberately adversarial cleartexts, but a sentence or more should work fine.

@Rikair thought I should put it on here, so I spruced it up a bit, allowing capital letters and punctuation.

I also calculate the KL-Divergence between the English and cypher text distributions as a more correct way of computing distribution similarity.
