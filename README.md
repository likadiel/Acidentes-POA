# Acidentes-POA
Visualização de métricas de acidentes de trânsito em Porto Alegre

Requirements:
> Python (obvious :P)
> Flask

Setup:
1. Unzip the files on dados/dados.zip
2. python rebuild_database.py
3. python run.py 

Endpoints (all based on http://localhost:5000):
> / : main view
> /query/top/<int:n> : get the total top <n> vias with accidents
> /query/top/<campo>/<int:n> : get the <campo> top <n> vias with accidents
> /db/<int:index> : get the json from the row where ID = <index> 
