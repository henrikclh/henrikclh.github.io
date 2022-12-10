# Practice practical AI

Mainly following [Fast.ai course](https://course.fast.ai/) lesson 1 and 2 by Jeremy Howard.
It is encouraging that Jeremy Howard explicitly mentioned:

*Here’s a few things you absolutely don’t need to do world-class deep learning:*

| **Myth(don't need)** | **Truth** |
| - | - |
| Lots of math | Just high school math is sufficient |
| Lots of data | We’ve seen record-breaking results with <50 items of data |
| Lots of expensive computers | You can get what you need for state of the art work for free |
	


## Lesson 1, trained the first model: 
I followed the 3 time study as the course suggested (1st time: watch the full video, 2nd time: watch and pause, code, loop..., 3rd time: try to do with own database)
I then attempted to build a own programme [Coop Himmelblau, WOHA or David Chipperfield designed it?](https://colab.research.google.com/drive/1UQZVPqy_3JtbmStc62pOPSUTi3NdDJ9O?usp=sharing)

Things learnt:
- Through actual training model, gained better both understanding and intuition on how to make good use of the great fastai library (from fast data collection (much faster than traditional web scraping) > Datablock > DataLoaders for training > finetune) 
- how to execute jupyter notebook locally

Things I haven't done enough:
- how to clean the data
- how to resolve overfitting by adjusting learning rate (sometimes overfitting...) 

Things I am curious but lower priority...
- how to display explanable ai

## Lesson 2, learnt to deploy a model (make 'codes' into an app)  
Deployed a trained model prepared by the course via huggingface [Cat or dog?](https://huggingface.co/spaces/henrikclh/test1)

Throughout the process, I learnt to set up Linux environment (mainly for git pushing via huggingface)

Things I am curious but lower priority...
- deploy .pkl with the model from Lesson 1!

## To do next...
- NLP!!!
- collaborative filtering!!
