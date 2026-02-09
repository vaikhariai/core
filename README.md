<div align="center">

# <img src="./images/logos/core.svg" width="30" />&nbsp;&nbsp;&nbsp;CORE: Comprehensive Ontological Relation Evaluation

🌐 [Website](https://core.vaikhari.ai) | 📄 [Paper](https://arxiv.org/abs/2602.06446) | 🤗 [Dataset](https://huggingface.co/datasets/vaikhari-ai/core)
</div>

CORE is a human-grounded benchmark for evaluating large language models on fundamental semantic and ontological reasoning. It assesses whether models can correctly recognize a broad range of sense-level relations and, critically, identify when no meaningful relationship exists between concepts. With comprehensive relation coverage and strong human baselines, CORE is designed to reveal systematic failure modes such as confidence–accuracy misalignment, semantic collapse, and overconfident reasoning that diverges from human judgment.

#### Load the dataset:

```python
from datasets import load_dataset

dataset = load_dataset("vaikhari-ai/core", split="test")
```

## ✏️ Citation

If you use CORE in your research, please cite our work.

```
@misc{dwivedi2026corecomprehensiveontologicalrelation,
      title={CORE: Comprehensive Ontological Relation Evaluation for Large Language Models}, 
      author={Satyam Dwivedi and Sanjukta Ghosh and Shivam Dwivedi and Nishi Kumari and Anil Thakur and Anurag Purushottam and Deepak Alok and Praveen Gatla and Manjuprasad B and Bipasha Patgiri},
      year={2026},
      eprint={2602.06446},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2602.06446}, 
}
```

## Licensing
This dataset is distributed under the CC BY-NC-ND 4.0 license and is intended solely for research and evaluation. See the repository’s [LICENSE](LICENSE.md) file for detailed usage conditions. Any commercial use, redistribution, or modification of the benchmark requires prior written approval.

----
For any inquiries or feedback, please contact us at [connect@vaikhari.ai](mailto:connect@vaikhari.ai).