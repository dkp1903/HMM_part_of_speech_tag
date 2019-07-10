# Part of Speech Tagging with Hidden Markov Models (HMM)
## https://medium.com/@patrickhk/part-of-speech-tagging-with-hidden-markov-models-hmm-4224cb72e9b9

This is the first project of my udacity NLP nanodegree. Honestly I think Hidden Markov Models is no longer important in NLP as now we have recurrent neural network. However for the task of part of speech tagging Hidden Markov Models is still practical and easy to train.<br/>

Udacity provide us with several helper functions so is much easier to implement. Lets see how to build most frequency class(MFC) tagger and Hidden Markov Models tagger(HMM).<br/>

### Dataset
We will use the Brown Corpus from the NLTK library<br/>

![p1](https://miro.medium.com/max/212/1*R30IWDsz15yQAZgA7smVoA.png)<br/>
Each sentence starts with a unique identifier on the first line, then followed by one tab-separated word/tag pair on each following line. (b100–5507 is the unique identifier.)<br/>
With the helper function from udacity we can easily build the dataset from the raw txt files.<br/>


![p2](https://miro.medium.com/max/700/1*dPh0lVvwlRzKXiam8A-gxA.png)<br/>
Just some stat about our corpus<br/>


![p3](https://miro.medium.com/max/695/1*MyITHwNQCqQuzghudrA5tw.png)<br/>
### Extract the pos tag and word token data
tags = [tag for word, tag in data.stream()]<br/>
words = [word for word, tag in data.stream()]<br/>

### For the rest of the code please refer to the jupyter notebook or medium post

-------------------------------------------------------------------------------------------------------------------------------------
### More about me
[[:pencil:My Medium]](https://medium.com/@patrickhk)<br/>
[[:house_with_garden:My Website]](https://www.fiyeroleung.com/)<br/>
[[:space_invader:	My Github]](https://github.com/fiyero)<br/>
