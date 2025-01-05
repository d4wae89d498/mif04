```bash
python -m venv venv
source venv/bin/activate
pip install jupyter ipykernel numpy pandas scikit-learn matplotlib seaborn scipy statsmodels
python -m ipykernel install --user --name=".venv" --display-name="Virtual"
```