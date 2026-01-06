# passenger_prediction

This repository will hold code, notebooks, data, and models for passenger prediction experiments.

Quick start — uploading files

- Upload via GitHub web UI:
  1. Open the repository on GitHub: https://github.com/dcruzlupen-png/passenger_prediction
  2. Click "Add file" → "Upload files".
  3. Drag & drop files or choose them on disk, then commit.

- Upload via Git (recommended for many files):
  - Clone: `git clone git@github.com:dcruzlupen-png/passenger_prediction.git`
  - Add files: `git add path/to/file`
  - Commit and push: `git commit -m "Add files"` && `git push`

Large files and Git LFS

If you will store large datasets or model weights, use Git LFS to avoid hitting repository limits:

1. Install Git LFS: `git lfs install`
2. Track file types (example): `git lfs track "*.csv" "*.parquet" "*.pt"`
3. Commit the `.gitattributes` file that lists tracked patterns: `git add .gitattributes && git commit -m "Track large files with Git LFS"`
4. Push as usual: `git push`.

Recommended repository structure

- `data/` — raw and processed datasets (consider using Git LFS or keep large files out of the repo)
- `notebooks/` — exploratory notebooks
- `src/` — source code and modules
- `models/` — trained model artifacts (use Git LFS)

Files added in this commit

- `README.md` — this file, with upload instructions
- `.gitignore` — typical Python / Jupyter / env ignores
- `.gitattributes` — patterns configured for Git LFS
- `data/.gitkeep` — keeps the `data/` directory in the repository

If you'd like a license added or CI set up, I can add those next.
