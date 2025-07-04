# human-eval-llm-simplification
We provide large-scale human annotations assessing LLM performance on sentence simplification:
| Evaluation Type        | Samples Annotated | Dimensions |
|------------------------|------------------|-------------|
| **Error Identification** | 4k+ complex-simple pairs | 7 error categories |
| **Likert-scale Rating** | 10k+ complex-simple pairs | Fluency, Meaning, Simplicity |

⚠️ IMPORTANT: In this repository, we excluded evaluations on the Newsela dataset due to licensing restrictions.
To obtain the complete evaluation data, please: 
1. Request access through Newsela's official website:  
   [https://newsela.com/data/](https://newsela.com/data/)
2. After obtaining permission, contact the author:  
  Xuanxin Wu [xuanxin.wu@ist.osaka-u.ac.jp](mailto:xuanxin.wu@ist.osaka-u.ac.jp)

Annotation files are available in the `/annotation` directory. Please refer to the README file for more information.

# Please cite the following paper if you use the above resources for your research.
```
@article{10.1145/3744744,
author = {WU, Xuanxin and Arase, Yuki},
title = {An In-depth Evaluation of Large Language Models in Sentence Simplification with Error-based Human Assessment},
year = {2025},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
issn = {2157-6904},
url = {https://doi.org/10.1145/3744744},
doi = {10.1145/3744744},
journal = {ACM Trans. Intell. Syst. Technol.},
note = {Just Accepted},
month = jun
}
```
