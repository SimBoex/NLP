# Translator_Transformer

After quite some problems for the debugging part, I found an interesting and useful implementation for a TRANSFORMER architecture from [here](https://machinelearningmastery.com/building-transformer-models-with-attention-crash-course-build-a-neural-machine-translator-in-12-days/). I basically copied and pasted its implementation after studying how it was done.

This was an opportunity to review the Transformer architecture, learn how to implement it for an easy debug phase and finally also how to pre-process the data for this translation task (ITALIAN TO ENGLISH).

Some useful links:
- [Architecture notes](https://github.com/SimBoex/Translator_Transformer/blob/187cf9bd84eea6d69054dc52ab7960ce552c6443/Theory_notebook.ipynb)
- [notebook](https://github.com/SimBoex/Translator_Transformer/blob/187cf9bd84eea6d69054dc52ab7960ce552c6443/MyTranslator.ipynb)
- [implementation](https://github.com/SimBoex/Translator_Transformer/blob/69daf079a31917f4124497a6eb3b89e56baa4fd7/transformer.py)



Problems:
- the training works in local but not on GOOGLE COLAB. (GRAPH EXECUTION ERROR)  ---> Now is solved (after updating the tensorflow library)

  
  


