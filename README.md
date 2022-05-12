# layoutlmv3_cord
Fine tune LayoutLMV3 on CORD dataset for receipt understanding

I Used the LayoutLMV3 implementation from https://github.com/NielsRogge/transformers/tree/add_layoutlmv3

## Results
| Dataset    | F1 Score | Precision | Recall |
|------------|----------|-----------|--------|
| Validation | 92       | 92        | 92     |
| Test       | 91       | 90        | 92     |

I could not get the f1-score of 96 as claimed in paper.
