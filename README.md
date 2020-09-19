# Introduction-Of-TextVQA
A brief introduction about textvqa
## Example
![image](https://github.com/JayZhu0104/Introduction-About-TextVQA/blob/master/img/example%20picture.png)
## Datasets
| Datasets | Features | Web | Paper |
| :---:  | :---:  | :---:  | :---:  |
| TextVQA| 1.General picture<br>2.OCR identification information provided by dataset official<br>3.Textvqa challenge dataset | https://textvqa.org | https://arxiv.org/abs/1904.08920 |
| ST-VQA | 1.General picture<br>2.According to different tasks, the official provides different OCR identification | https://rrc.cvc.uab.es/?ch=11&com=introduction | https://arxiv.org/abs/1905.13648 |
| OCR-VQA | Book cover picture | https://ocr-vqa.github.io | https://anandmishra22.github.io/files/mishra-OCR-VQA.pdf |

## Models
| Models | Features | Accuracy(TextVQA Test dataset) | Paper |
| :---:  | :---: | :---: | :---: |
| DiagNet| MFB&MFH + OCR | 18.77 | https://w-yi.github.io/projects/diagnet/report.pdf | 
| LoRRA| Original model | 27.63 | https://arxiv.org/abs/1904.08920 | 
| MM-GNN | Graph neural network | 32.46 | https://arxiv.org/abs/2003.13962 |
| M4C | Transformer | 40.46 | https://arxiv.org/abs/1911.06258 |
| SA-M4C | Transformer | 44.6 | https://arxiv.org/pdf/2007.12146.pdf |
| SMA | Graph neural network | 45.51 | https://arxiv.org/abs/2006.00753 |

* Recommended reading model: LoRRA; M4C; SA-M4C; SMA
