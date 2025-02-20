# Relation Extraction

## Dataset
### How to Acquire and Pre-Process
1. Download the `train_wiki.json` and `val_wiki.json` dataset files from the [FewRel GitHub repository](https://github.com/thunlp/FewRel/tree/master) (~20MB) and move them inside `models/raw`.
2. Open the `dataset/dataset_preprocessing.ipynb` notebook.
3. Run the code cell to pre-process the data into training, validation, and testing splits which will be saved inside the `dataset` folder.

## Transformer Model
### How to Run the Demo
1. Download the trained model weights from [Google Drive](https://drive.google.com/file/d/1uKSeuQqHLkwXNS2lk4gMylQwRmoqvNIo/view?usp=drive_link) (~450MB) and move them to `models/transformer.pt`.
2. Open the `models/transformer.ipynb` notebook.
3. Run the first (`Options`) and second (`Transformer Model`) code cells.
4. Run the final (`Model Demo`) code cell.
5. Enter input sentences (including entity delimiters, as described in the notebook) to see the predicted relations and their corresponding probabilities.
6. Enter no input to end the demo.