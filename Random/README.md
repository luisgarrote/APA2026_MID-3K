# Dataset train/test split

Deterministic 80/20 train/test split stratified by the `DEPARTMENT` field in `metainfo.csv`.

- Random seed: `42`
- Total records: 3,083
- Image and label files remain in the original `images/` and `labels/` directories.
- `train.txt` and `test.txt` list image paths relative to the repository root.
- `train.csv` and `test.csv` include the original metadata plus `IMAGE_PATH` and `LABEL_PATH`.

| Split | Total | DEEC | DEI |
|---|---:|---:|---:|
| Train | 2,466 | 1,170 | 1,296 |
| Test | 617 | 293 | 324 |
| Total | 3,083 | 1,463 | 1,620 |
