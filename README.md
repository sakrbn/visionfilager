# visionfilager
%%bash
cat > README.md << 'EOF'
# Fingerprint Recognition on FVC2002

This project includes:
- Extraction and preprocessing of the FVC2002 dataset
- Fine-tuning of InceptionResnetV1 with a simple classification head
- Automatic early stopping when accuracy ≥ 75% is reached
- Measurement of single-image inference time
- Construction of an enrollment database of averaged fingerprint embeddings

**Usage**
```bash
python train_fvc2002.py
