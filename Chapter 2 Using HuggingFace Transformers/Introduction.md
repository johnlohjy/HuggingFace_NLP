# Benefits of Hugging Face

## Complications of training and deployment
Transformer models are usually very large: They have millions to tens of billions of parameters whch makes training and deploying these models a complicated undertaking

## Competitiveness 
New models are being released on a near-daily basis with each having their own implementation - trying them all out is no easy task either

## Hugging Face Transformer Library
The goal of the library is to provide a single API through which any Transformer model can be loaded, trained, and saved

The library's main features are:
- Ease of Use: Downloading, loading, and using a state-of-the-art NLP model for inference can be done in just two lines of code

- Flexibility: At their core, all models are simple PyTorch nn.Module or TensorFlow tf.keras.Model classes and can be handled like any other models in their respective machine learning (ML) frameworks

- Simplicity: Hardly any abstractions are made across the library. The “All in one file” is a core concept: a model’s forward pass is entirely defined in a single file, so that the code itself is understandable and hackable (all the code is there, easy for users to understand)