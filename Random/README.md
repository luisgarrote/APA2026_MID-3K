# Dataset train/test split

Deterministic 80/20 train/test split stratified by the `DEPARTMENT` field.

- Total records: 3,083
- Image and label files remain in the original MID-3K `images/` and `labels/` directories.
- `train.txt` and `test.txt` list image paths relative to the repository root.

| Split | Total | DEEC | DEI |
|---|---:|---:|---:|
| Train | 2,466 | 1,170 | 1,296 |
| Test | 617 | 293 | 324 |
| Total | 3,083 | 1,463 | 1,620 |
