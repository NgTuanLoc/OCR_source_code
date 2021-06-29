# Vietnamese Handwritting Regconition with Transformer and Lstm&Attention

## Installation

```bash
pip3 install -r requirements.txt
```

## Model Method

### A/ Lstm & Attention

    .
    ├── data                   # Folder containing image data
    ├── labels                 # Folder containing label.json
    ├── test                   # Put your images that need to be predicted in this folder
    ├── predict                # Your prediction will be in this folder
    ├── weights                # your trained modelfolder

**For training your Data**

If you place your data exactly like above file structure just run this command

```bash
python3 crnn.py --epochs {number of epoch} --batch_size {number of batch size}
```

**For training your Data**

```bash
python3 predict.py
```

### B/ Transformer

**Read transformer_tutorial.ipynb for more information**
