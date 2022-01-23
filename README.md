# Machine_Translation_Encoder_Decoder
This is a repository for an end-to-end Machine Translation project, which uses a neural network trained on a small dataset of English and French text. Written as part of a Udacity project, the encoder-decoder functions as part of an end-to-end machine translation pipeline. The completed pipeline will accept English text as input 
and return the French translation. A data processing pipeline is set up, before the model is called. The model is built using TensorFlow/Keras, and uses GPU acceleration for training.

## Install
- Python 3
- NumPy
- TensorFlow 2.x
- Keras 2.x

# Future Improvements

Need to add an evaluation metric (like BLEU score) to the code. Adding an attention mechanism (e.g. Luong et al) to the decoder (alternatively, using a Transformer model like BERT) will improve the training and test results.
