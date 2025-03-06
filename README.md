# Relation Extraction

## Dataset
### How to Acquire and Pre-Process
**NOTE: Our pre-processed dataset splits are already provided within the `dataset` folder, therefore the following is optional.**
1. Download the `train_wiki.json` and `val_wiki.json` dataset files from the [FewRel GitHub repository](https://github.com/thunlp/FewRel/tree/master) (~20MB) and move them inside `dataset/raw`.
2. Open the `dataset/dataset_preprocessing.ipynb` notebook.
3. Run the code cell to pre-process the data into training, validation, and testing splits which will be saved inside the `dataset` folder.

## CNN Model
### How to Run the Demo
1. Download the trained model archive from [OneDrive](https://livemanchesterac-my.sharepoint.com/:u:/g/personal/omar_badawi-2_student_manchester_ac_uk/EQkCZi6Gg31Omdah4KfvPawBuctBIkMtzcBmdpA80Rm1zA?e=C8Z2ok). The archive also contains tuning iterations along with their respective model weights.
2. Unzip the `cnn` folder and move it into `models/` directory.
2. Open the `models/cnn_demo.ipynb` notebook.
3. Run all code cells.
5. Enter input sentences (including entity delimiters, as described in the notebook) to see the predicted relations and their corresponding confidence scores.
6. Enter no input to end the demo.

## Transformer Model
### How to Run the Demo
1. Download the trained model weights from [Google Drive](https://drive.google.com/file/d/1uKSeuQqHLkwXNS2lk4gMylQwRmoqvNIo/view?usp=drive_link) (~450MB) and move them to `models/transformer.pt`.
2. Open the `models/transformer.ipynb` notebook.
3. Run the first (`Options`) and second (`Transformer Model`) code cells.
4. Run the final (`Model Demo`) code cell.
5. Enter input sentences (including entity delimiters, as described in the notebook) to see the predicted relations and their corresponding confidence scores.
6. Enter no input to end the demo.
