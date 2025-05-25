## Overview 
### Datasets Used
| ID       | Dataset | 
|----------|---------|
| `turk`   | TURK (test set) |
| `asset`  | ASSET (test set) | 
| `newsela`| Newsela (test set) | 
| `simpa`  | SimPA | 
| `human`  | Newsela reference sentences |

> **Note**: 
> - SimPA originally contains 1,100 complex-simple pairs (lexical + syntactic versions). Three samples were used for few-shot prompting.
> In **Likert-scale rating**, we also evaluated the **reference simplifications** from the Newsela test set for comparison.

### Models Evaluated
| ID       | Model |
|----------|-------|
| `gpt`    | GPT-4 |
| `qwen`   | Qwen2.5-72B |
| `llama`  | Llama-3.2-3B |
| `t5`     | Control-T5 |
| `human`  | Newsela reference |

### Error Types Annotated
Annotators collaboratively identified these error types:
| ID                | Full Name |
|-------------------|-----------|
| Lack of Sim-L   | Lack of Sim-Lexical |
| Lack of Sim-S   | Lack of Sim-Structural |
| Altered Meaning-L | Altered Meaning-Lexical |
| Altered Meaning-S | Altered Meaning-Structural |
| Coreference     | Coreference |
| Repetition      | Repetition |
| Hallucination   | Hallucination |
| No error        | No error (final character labeled) |