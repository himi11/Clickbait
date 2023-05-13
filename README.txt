





SPOILER CLASSIFICATION


Model (multi-class classification - Spoiler Type ))		F1 Score
BERT (base uncased)						61.16ROBERTA ( base )						70.38DistilBERT							65.01Longformer							67.56GPT-3 ( Ada - Prompt 1)						68.50GPT-3 ( Ada - Prompt 2)						67.22GPT-3 ( Curie - Prompt 3)					70.02
SPOILER GENERATION (PHRASE)


PHRASEModel		BLEU		Meteor		BERT Score
BERT*		0.21		0.48		60.34ROBERTA*	0.31		0.59		71.51Long T5*	0.5473		0.5991		96.68LED*		0.553		0.5764		96.24T5(T5-small)	0.64		0.55Bart		0.20		0.27SPOILER GENERATION (PASSAGE)


PASSAGEModel		BLEU		Meteor		BERT ScoreBERT*		0.13		0.27		20.63ROBERTA*	0.17		0.27		24.25Long T5*	0.891		0.9069		98.16LED*		0.853		0.8857		97.70T5(T5-small)	0.49		0.62Bart		0.18		0.25

SPOILER GENERATION (MULTI)


MULTIModel		BLEU		Meteor		BERT ScoreBERT*		0.032		0.12		14.05ROBERTA*	0.025		0.12		13.86Long T5*	0.8185		0.8620		96.57LED*		0.7546		0.8254		95.79T5(T5-small)	0.5		0.7Bart		0.17		0.22