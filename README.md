# Machine_Translation_Encoder_Decoder
This is a repository for an end-to-end Machine Translation project, which uses an encoder-decoder neural network trained on a small data. As part of a Udacity project, 
I built an encoder-decoder neural network that functions as part of an end-to-end machine translation pipeline. The completed pipeline will accept English text as input 
and return the French translation. The code used GPU acceleration and was run on my personal gaming laptop.

## Install
- Python 3
- NumPy
- TensorFlow 2.x
- Keras 2.x

# Future Improvements

Need to add an evaluation metric (like BLEU score) to the code. Adding an attention mechanism (e.g. Luong et al) to the decoder (alternatively, using a Transformer model like BERT) will improve the training and test results.
