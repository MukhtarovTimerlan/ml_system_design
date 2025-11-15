# News Assistant AI  
  
Строим RAG систему на основе новостей из публичного ТГ-канала при помощи API  
  
## Статус  
- Статус разработки: `WIP`  
  
## Ожидаемый результат  
  
Ассистента развернуть на локальном хосте. Front реализовать через streamlit. После ответа от модели привести краткие цитирования и ссылки на источники контекста (новостей)  
  
## Быстрый старт  
  
### Требования  
- Python 3.11+  
- virtualenv  
  
### Установка  
```bash
git clone git@github.com:MukhtarovTimerlan/ml_system_design.git  
cd repo  
python -m venv .venv  
source .venv/bin/activate  
pip install -r requirements.txt  

### Линтер и pre-commit
```bash
pip install ruff pre-commit  
pre-commit install  
pre-commit run --all-files  

### Структура
repo/
├─ .git/
├─ pyproject.toml        
├─ .pre-commit-config.yaml
├─ .gitignore  
├─ README.md  
└─ src/

### Контакты 
Мухтаров Т.Т. tg: @mrtimax