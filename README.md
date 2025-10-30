# islp
repositorio para estudos do livro introduction to statistical learning

1. Clone o repositorio: 
```bash
https://github.com/danieltodaDS/islp.git
cd ~/islp
```

2. Configure a versao correta do Python com `pyenv`: 
```bash
pyenv install 3.12.1
pyenv local 3.12.1
```

3. Instale as dependencias do projeto: 
```bash
python -m venv .venv
source .venv/bin/activate #Linux
source .venv\\Scripts\\Activate #Windows
pip install -r requirements.txt
```

----------------

- Para atualizar dependencias: 

```bash
pip list --not-required --format=freeze >> requirements.txt
```

