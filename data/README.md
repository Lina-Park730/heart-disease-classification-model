# Dataset

`heart_disease_midterm.csv` is the coursework dataset used in this analysis. The original file is retained without edits. Cleaning is applied in memory by the training script.

| Column | Role | Recorded values |
| --- | --- | --- |
| `age` | Numeric predictor | 29–77 |
| `sex` | Binary predictor | 0, 1 |
| `chest.pain` | Binary predictor | 0, 1 |
| `bp` | Numeric predictor | 94–200 |
| `chol` | Numeric predictor | 126–564 |
| `disease` | Target | `no`, `yes` |

The file contains 300 rows, no missing values, and one exact duplicate. Removing the duplicate leaves 299 rows: 161 `no` and 138 `yes`.

The original source, license, measurement units, and category definitions were not included with the CSV. Column names are retained, binary codes are used as recorded, and `yes` is treated as the positive class. No equivalence to a specific public clinical dataset is assumed. The source and redistribution terms remain unverified.
