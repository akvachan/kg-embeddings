## Info

- **Visualization:** Tensorboard
- **Embedding Models:** TransE, DistMult, ComplEx, ConvE
- **Evaluation Metrics:** Hits10, Mean

## Embeddings

- WN18: `embeddings-wn18.pkl`
- Custom Dataset: `embeddings-medical-knowledge-graph.pkl`

## Datasets

- WN18: 150k Triplets
- Custom Dataset: 0.5k Triplets (`medical-knowledge-graph.csv`)

## Evaluation Results

| Model   | WN18 (hits10/mean) | Custom Dataset (hits10/mean) |
| ------- | ------------------ | ---------------------------- |
| TransE  | 0/0                | 0/0                          |
| DistMult| 0/0                | 0/0                          |
| ComplEx | 0/0                | 0/0                          |
| ConvE   | 0/0                | 0/0                          |

## WARNING

**Medical knowledge graph is a randomly generated dataset by GPT. It contains NO REAL MEDICAL DATA. It must be used for illustration purposes only, to test embedding algorithms on unbiased, custom datasets.**
