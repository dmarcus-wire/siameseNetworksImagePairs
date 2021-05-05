# Siamese Network

- Fun architecture
- Simple to advanced architectues
- signet (signature verification) = real/fraud
    - the two individual inputs, like signatures
    - there are two separate network architectures
    - with identical bodies
    - weight updates are also identical
- positive pair
- negative pair
- generating image pairs is the cornerstone
- you CANNOT TRAIN without understanding
    
- more advanced include 3 inputs
- real work
  - Face recognition: Given two separate images containing a face, determine if it’s the same person in both photos.
  - Signature verification: When presented with two signatures, determine if one is a forgery or not.
  - Prescription pill identification: Given two prescription pills, determine if they are the same medication or different medications.
  - content based image retreival (return similar)
  
Popular loss functions when training siamese networks include:

- Binary cross-entropy
- Triplet loss
- Contrastive loss

We’ll be using the MNIST digits dataset as our sample dataset (for convenience purposes). That said, our make_pairs function will work with any image dataset, provided you supply two separate image and labels arrays (which you’ll learn how to do in the next code block).
