# Neural Language Model Training Using PyTorch
This project demonstrates training a neural language model from scratch using PyTorch. Preprocessing, tokenization, and batching are implemented using only PyTorch and standard Python tools.

## Project Structure

```
NLM/
│── plots/
│    ├── loss_curve_128x256.png
│    ├── loss_curve_256x512.png
│    ├── loss_curve_32x64.png
│    ├── perplexity_curve_128x256.png
│    ├── perplexity_curve_256x512.png
│    ├── perplexity_curve_32x64.png
│── Pride_and_Prejudice-Jane_Austen.txt
│── model.ipynb
│── NLM_Assignment.pdf
│── README.md
```

## Running Project

1. Install dependencies
   ``` bash
   pip install matplotlib torch tqdm
   ```
2. Open a notebook
3. Run all the cells to train the model and generate plots
