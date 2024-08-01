<img width="769" alt="Screenshot 2024-08-01 at 6 37 46 AM" src="https://github.com/user-attachments/assets/89e17787-e1e5-4aa0-89fa-68f6231b90e4">

Input Layer: Specifies the input shape, which is a sequence of word indices.

Embedding Layer: Converts word indices into dense vectors (embeddings) to represent the words in a higher-dimensional space.

Bidirectional LSTM Layer: Processes the sequence in both directions to capture context from past and future words.

TimeDistributed Dense Layer: Applies a Dense layer to each time step to predict the entity tag for each word.

Model Construction: Combines the layers into a complete model that can be trained and evaluated.
