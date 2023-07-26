# Mastermind

This is a very simple jupyter notebook that compares two mastermind strategies:
- the first strategy is just picking a fully random set of colours that works with all rpevious guesses
- the second strategy is starting with aaaa, then if there is one a trying abbb, etc.

I wanted to see which was quicker, and overwhelmingly it is the first strategy. Cool!

The rules we use are:
- if the code is ABCD and you guess AABE, you will get "[0,0,1,2]" meaning 1 letter was correctly placed and 1 was not correctly placed, but it doesn't specify which ones.

  
