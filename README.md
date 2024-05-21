# TodoList

## Rodar localmente com SQLite

```
# clonar repo
git clone git@github.com:huogerac/djangoargo.git
cd djangoargo

# Criar virtualenv e instalar dependencias
python -m virtualenv .venv
source .venv/bin/activate
pip install -r requirements-dev.txt


# Iniciar Django
./manage.py migrate
./manage.py runserver

```


## Organização

- App `theme` armazena os arquivos de frontend e template [Argon](https://demos.creative-tim.com/argon-design-system/docs/getting-started/overview.html)
- O `theme/argo.html` é a base para os templates e é totalmente extensível com os blocos
- Utiliza o [django-widget-tweaks](https://github.com/jazzband/django-widget-tweaks) para adicionar CSS extras as páginas e forms (ao invés de ter que colocar CSS nos forms.py)
