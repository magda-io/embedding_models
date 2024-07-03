# Magda Embedding Models

Release a list of embedding models in ONNX format for the Magda project:
- [gte-base-en-v1.5](https://github.com/magda-io/embedding_models/releases/tag/gte-base-en-v1.5)
- [gte-large-en-v1.5](https://github.com/magda-io/embedding_models/releases/tag/gte-large-en-v1.5)

### Release model

- Download ONNX model file (or [convert model](https://github.com/xenova/transformers.js?tab=readme-ov-file#convert-your-models-to-onnx) to ONNX format)
- Save model file (ONNX model) and tokenizer.json to the same folder
- Run `zip -r -X model.zip *`
- Run `shasum -a 256 model.zip` to generate SHA-256 hash
- Run `ls -l` to get model file size 
