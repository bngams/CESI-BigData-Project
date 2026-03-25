# Data

This folder contains all data sources required for the HDF project.
Some files are managed with **Git LFS** (Large File Storage) — follow the steps below to make sure you download everything correctly.

---

## Clone the repository

### 1. Install Git LFS (once per machine)

```bash
# Ubuntu / Debian
sudo apt install git-lfs

# macOS
brew install git-lfs

# Windows (via Chocolatey)
choco install git-lfs
```

Then activate it globally:

```bash
git lfs install
```

### 2. Clone the repository

```bash
git clone https://github.com/bngams/CESI-BigData-Project.git
cd CESI-BigData-Project
```

Git LFS files are downloaded automatically during clone if `git lfs install` was run beforehand.

### 3. If you already cloned without LFS

If you cloned the repo before installing Git LFS, run:

```bash
git lfs pull
```

This will download all LFS-tracked files that were skipped.

---

## Verify your data

To check which files are tracked by LFS:

```bash
git lfs ls-files
```

To check the status of LFS files in your local copy:

```bash
git lfs status
```
