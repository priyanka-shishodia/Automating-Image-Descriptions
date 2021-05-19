# Generating Image Descriptions: Aid for the Visually Impaired

Automating image descriptions is a classic and challenging artificial intelligence problem. The importance of Image captioning in real-world scenarios is in self-driving cars, Google Image Search and Security data annotation, among others. One such application notably being providing aid to the visually impaired.

In this project, the idea is to develop an architecture that generates image descriptions using its predicted features. The model includes – (1) a Convolutional Neural Networks (InceptionV3) to extract image features and (2) an LSTM (Long short-term Memory) language model that decodes the joint embeddings of the image features and label captions. The overall architecture follows an encoder-decoder pipeline.

