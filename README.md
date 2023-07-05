# snapshot

Uses `nbconvert` and `puppeteer` to execute notebooks and produce static images for all outputs

## Usage

```bash
npm install
conda activate <myenv>
npm run snapshot <target-folder>
```

## Remaining tasks

- [ ] open original ipynb files and patch the images back in where approprirate
- [ ] add a pre scan of the ipynb file to collect cell-id's of the subset of celsl tat should have snapshots added
