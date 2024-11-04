<div align="center">

<h1>FlowCE: First Multi-Dimensional Evaluation of Flowchart Comprehension for Multimodal Large Language Models</h1>



<a href="https://arxiv.org/pdf/2406.10057"><img src="https://img.shields.io/badge/Paper-PDF-orange"></a>   [![Code License](https://img.shields.io/badge/Code%20License-Apache_2.0-green.svg)](https://github.com/tatsu-lab/stanford_alpaca/blob/main/LICENSE) [![Data License](https://img.shields.io/badge/Data%20License-CC%20By%20NC%204.0-red.svg)](https://github.com/tatsu-lab/stanford_alpaca/blob/main/DATA_LICENSE)

</div>
<p>

   With the development of Multimodal Large Language Models (MLLMs) technology, its general capabilities are increasingly powerful. To evaluate the various abilities of MLLMs, numerous evaluation systems have emerged. But now there is still a lack of a comprehensive method to evaluate MLLMs in the tasks related to flowcharts, which are very important in daily life and work. We propose the first comprehensive method, FlowCE, to assess MLLMs across various dimensions for tasks related to flowcharts. It encompasses evaluating MLLMs’ abilities in Reasoning, Localization Recognition, Information Extraction, Logical Verification, and Summarization on flowcharts. However, we find that even the GPT4o model achieves only a score of 56.63. Among open-source models, Phi-3-Vision obtained the highest score of 49.97. We hope that FlowCE can contribute to future research on MLLMs for tasks based on flowcharts.
</p>


## Release
- [ ]  release the evaluation script.  
- [x] 🔥🔥🔥 We release the dataset (https://github.com/360AILABNLP/FlowCE/tree/main/flowce_benchmark).

**Usage and License Notices**: The data, code, and checkpoint are intended and licensed for research use only. They are also restricted to use that follow the license agreement of LLaMA, Vicuna, GPT-4, Qwen, and LLaVA. 


## FlowCE Benchmark Dataset

FlowCE is built upon 500 real-world flowcharts, ensuring an ample diversity in each chart and across five dimensions in real flowchart scenarios, including reasoning, information extraction, localization recognition, summarization, and logical verification.

<img width="754" alt="image" src="https://github.com/user-attachments/assets/de4c798e-d5bd-4d8f-b8e3-19ce0ae05638">

The full datasets can be obtained from the following address: https://github.com/360AILABNLP/FlowCE/tree/main/flowce_benchmark

For your attention: The image data used in this work is solely for scientific research purposes, and only the source link address for each image is made available. if you want to get the images, just download these images from the 5 different task image urls file given. 

## Process of creating and evaluating FlowCE

![route](https://github.com/user-attachments/assets/0671251c-46c0-4fad-8f3f-f62f190a7b05)

## Data samples of FlowCE

<img width="760" alt="image" src="https://github.com/user-attachments/assets/dc3501c6-8549-47f3-bd8d-31bab9edb332">

covers 5 evaluation dimensions. Each evaluation dimension contains human-annotated question-answer pairs.

## Result

**1. Statistics of compared API-based and open-source MLLMs**

<img width="945" alt="image" src="https://github.com/user-attachments/assets/94b0dbfa-cc70-48cf-b781-bc04016e2462">

**2.Detailed evaluation results on FlowCE across different models**

<img width="811" alt="image" src="https://github.com/user-attachments/assets/98c402fc-c22c-48c7-8a8c-212e1ea2cec8">


## License

The content of this project itself is licensed under [LICENSE](LICENSE).


