# Machine_Translation_Encoder_Decoder
This is a repository for an end-to-end Machine Translation project, which uses a neural network trained on a small dataset of English and French text. Written as part of a Udacity project, the encoder-decoder functions as part of an end-to-end machine translation pipeline. The completed pipeline will accept English text as input 
and return the French translation. A data processing pipeline is set up, before the model is called. The model is built using TensorFlow/Keras, and uses GPU acceleration for training.

The unique features of the model are (a) the use of an embedding layer, which improves validation accuracy tremendously, and (b) a finely tuned dropout before the TimeDistributed Dense layer, which also helps improve the validation and test accuracy; combined, these features result an an accuracy of over 98%. An encoder-decoder with attention architecture has been used in Google Translate (but is of course a much larger and much more sophisticated model, trained on a larger dataset).

## Install
- Python 3
- NumPy
- TensorFlow 2.x
- Keras 2.x

# Future Improvements

Need to add an evaluation metric (like BLEU score) to the code. Adding an attention mechanism (e.g. multi-head attention using a scaled dot-product attention) to the decoder will further improve the results. The current state-of-the-art for NMT is the Transformer, which would need to be trained on a much larger dataset.
