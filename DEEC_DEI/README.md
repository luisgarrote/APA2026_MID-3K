# Department-held-out split: DEEC to DEI

All DEEC records are assigned to training and all DEI records to testing. This split is intended to evaluate cross-department generalization.

- Train: 1,463 DEEC images
- Test: 1,620 DEI images
- Matching labels are referenced in the CSV manifests.
- The original image and label files remain in the repository-root `images/` and `labels/` folders.
- `.txt` manifests list image paths relative to the repository root; `.csv` manifests include all metainfo fields and image/label paths.
