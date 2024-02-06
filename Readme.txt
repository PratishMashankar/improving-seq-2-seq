                      Instruction for Execution
		      --------------------------

Introduction:
         Through this report we are genarating a English to French translation using seq2seq model  witout and with attention mechanism – a breakthrough concept that allows the model to dynamically focus on different parts of the input sequence while generating the output. Unlike a transformer layer, our goal is to implement attention as an augmentation to the existing Seq2Seq architecture, enhancing its ability to capture dependencies and nuances in the source language.


Platform and version:
	  python 3.10.9 
          tensor flow 2.13.0 

Required Python Libraries :
	numpy
	tensorflow
	keras - pad_sequences
	keras -Tokenizer
	keras - LSTM, GRU, Dense, Embedding
	Pillow
	tqdm
	matplotlib
	scikit-learn

Model Generation:
	Initially, we choose a target language for translation, ensuring the availability of a suitable parallel dataset for training and evaluation. We have chosen the language French for this assignment. We have received thesentence pairs from “manythings.org” portal. We evaluated the performance using seq2seq model with and without attention. We have used Glove 50 embeddings whoch are not included in the submission folder. The notebook is well formatted and best viewed in Google Colab




