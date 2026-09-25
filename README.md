# DSCI 552 Homework 2

Status: programming questions 1(a)–1(j) are complete with saved outputs. Textbook questions 2 and 3 and the GitHub username are still pending.

## Structure

- `notebook/Jiang_Shanglin_HW2.ipynb`: answers, code, and saved outputs.
- `data/CCPP/`: original supplied data files and documentation, preserved unchanged.
- `requirements.txt`: Python dependencies.

## Run locally

From the repository root, install dependencies into the environment used by your notebook:

```bash
python -m pip install -r requirements.txt
```

Open the notebook with `notebook/` as its working directory. Select the same Python environment in VS Code, restart its kernel, run all cells, and save the executed notebook.

For command-line execution from the repository root:

```bash
python -m nbconvert --to notebook --execute --inplace notebook/Jiang_Shanglin_HW2.ipynb
```

The data path is `../data/CCPP/Folds5x2_pp.xlsx`; only the first worksheet is used.

## Submission checklist

- Fill in the GitHub username in the first notebook cell.
- Complete textbook questions 2 and 3 once the problem statements are supplied.
- Restart the kernel and run all cells; retain all relevant outputs.
- Upload these root-level folders and files to the private repository created by the HW2 GitHub Classroom invitation. Do not upload an extra enclosing HW2 folder.
- Submit that repository's link according to the course instructions.

Reference PDFs, the original ZIP, and a backup of the initial notebook are preserved outside the submission folder in `../HW2_reference/`.
