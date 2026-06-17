# Detector
Coming Soon.

# Multi-Task Scientific Text Dataset

This repository contains a standardized JSONL version of a multi-task dataset for scientific text analysis. Each example pairs a generated scientific text with metadata about the text it was generated from, a SciBERT/BERT-Sci-based BERTScore regression target, and token-level binary labels aligned to `roberta-base` tokenization.

## Files

- `data/all-*.jsonl`: sharded dataset files. Each line is one JSON object.
- `data/dataset_info.json`: export metadata, including record counts and source-file counts.


