# ArtExtract Task 2 – Painting Similarity

## Approach
- Used CLIP model for image embeddings
- Computed cosine similarity for retrieval

## Dataset
- CIFAR-10 used for pipeline validation
- Scalable to art datasets

## Results
- Same-class similarity > Different-class similarity
- Demonstrates meaningful embedding space

## Limitations
- CIFAR is low-resolution
- Not domain-specific to paintings

## Future Work
- Fine-tune CLIP on art datasets
- Use metric learning
