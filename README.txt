

How to execute the code:

1.Select the model which you want to run, we have pasted the link of models below.
2.Upload train.jsonl and validation.jsonl of the dataset given in clickbait challenge https://pan.webis.de/semeval23/pan23-web/clickbait-challenge.html
3.Replace the path of the dataset in the jupyter notebook.
4.Execute the code cell by cell and you will get results.




SPOILER CLASSIFICATION


Model (multi-class classification - Spoiler Type ))		F1 Score

BERT (base uncased)		61.16 https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task1/transformers_train_bert_uncased.ipynb

ROBERTA ( base )			70.38 https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task1/transformers_train_roberta.ipynb

DistilBERT				65.01 https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task1/transformers_train_DistilBERT.ipynb

Longformer			67.56 https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task1/transformers_train_longformer.ipynb
GPT-3 ( Ada - Prompt 1)					68.50 https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task1/prompt1_ada.ipynb
GPT-3 ( Ada - Prompt 2)					67.22 https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task1/prompt2_ada.ipynb
GPT-3 ( Curie - Prompt 3)				70.02 https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task1/prompt3_curie.ipynb




SPOILER GENERATION (PHRASE)


PHRASE
Model		BLEU		Meteor		BERT Score

BERT*		0.25		0.48		60.34         https://github.com/himi11/Clickbait/blob/main/Himani/Milestone3/bert%20Phrase.ipynb
ROBERTA*	0.36		0.59		71.51       https://github.com/himi11/Clickbait/blob/main/Himani/Milestone3/roberta.ipynb
Long T5*	0.5473		0.5991		96.68   https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task2/phrase/longt5.ipynb
LED*		0.553		0.5764		96.24       https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task2/phrase/led.ipynb
T5 base*  0.55  0.61  0.97 `          https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task2/phrase/led.ipynb  




SPOILER GENERATION (PASSAGE)


PASSAGE
Model		BLEU		Meteor		BERT Score

BERT*		0.13		0.27		20.63       https://github.com/himi11/Clickbait/blob/main/Himani/Milestone3/BERT_passage.ipynb
MiniLM*	0.17		0.27		24.25       https://github.com/himi11/Clickbait/blob/main/Himani/Milestone3/MiniLM_passage.ipynb
Long T5*	0.891		0.9069		98.16   https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task2/passage/longt5.ipynb
LED*		0.853		0.8857		97.70     https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task2/passage/led.ipynb
T5 base 0.77    0.83    96.67       https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task2/passage/led.ipynb




SPOILER GENERATION (MULTI)


MULTI
Model		BLEU		Meteor		BERT Score

BERT*		0.032		0.12		14.05     https://github.com/himi11/Clickbait/blob/main/Himani/Milestone3/BERT_MULTI.ipynb
MiniLM*	0.025		0.12		13.86     https://github.com/himi11/Clickbait/blob/main/Himani/Milestone3/MiniLM_MULTI.ipynb
Long T5*	0.8185		0.8620		96.57 https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task2/multi/longt5.ipynb
LED*		0.7546		0.8254		95.79   https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task2/multi/led.ipynb
T5 base 0.59    0.69      93.15     https://github.com/himi11/Clickbait/blob/main/NLP%20Final%20Project%20Madhavan/final_milestone3/task2/multi/led.ipynb


