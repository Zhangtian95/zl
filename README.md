# Environment
python==3.7.12
***
pytorch==1.11.0

scikit learn==1.0.2 

matplotlib==3.5.1

# Usage

```python
conda create -n ZL python=3.7.12
conda activate ZL
pip install -r requirements.txt
python cora.ipynb
python Citeseer.ipynb
python PubMed.ipynb
```

# Result
| Dataset | Cora | Citeseer | Pubmed |
|:-: | :-: | :-: | :-: |
|Accuracy|0.8130|0.6850|0.7290|
|F1_score|0.8050|0.6482|0.7302|
|AUC|0.97|0.89|0.89|
