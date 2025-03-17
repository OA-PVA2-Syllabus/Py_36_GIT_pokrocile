# PVA2 - Programování a vývoj aplikací
## Cvičení 36: Git pro pokročilé

Tento repozitář slouží jako ukázka pro práci s GITem a GitHubem. Procvičíme si:

- **Branches:** Vytváření a slučování větví.
- **Pull Requesty:** Jak navrhnout změny a provést code review.
- **Issues:** Jak vytvářet a spravovat problémy či nápady na vylepšení.


# Úkoly

1. Příprava repozitáře
    - Vytvořte si vlastní fork tohoto repozitáře.
    - Prohlédněte si strukturu projektu, soubory a obsah.

2. Vytvoření větví:
   - Založte nový požadavek na novou funkcionalitu, kterou budete programovat. Funkci popište, vhodně označte štítky a typem a nastavte se jako řešitel.
   - Vytvořte novou větev pojmenovanou podle vzoru feature/nova-funkce a implementujte novou funkcionalitu.

3. Obsahové změny
   - Naprogramujte svou novou funkcionaltiu. Definice funkcí ukládáme výhradně do `utils.py`
   - Vytvořte nový soubor `.gitignore` a přidejte do něj obsah uvedený níže.
   - Aktualizujte/Vytvořte soubor readme-prijmeni.md o podrobný popis změn.

4. Uložení změn
    - Proveďte `commit` a `push` změn do vzdáleného repozitáře.
    - Popis změny musí odpovídat obsahu změn. 

5. Vytvoření Pull Request:
   - Vytvořte Pull Request z nové větve do main a požádejte souseda o code review.
   - Můžete také přidat komentáře k úpravám v rámci Pull Requestu.
   - V pull requestu bude zahrnut odkaz na související issue a stručný popis změn.

   - Revize kódu (Code review):
    - Přidělení recenzenta
      - Přidejte souseda nebo jiného spolužáka jako recenzenta. Zkontrolujte si, že recentenz není už přiřazen k žádnému úkolu. Každý bude recenzovat jen jednu funkci/pull request.
    - Co kontrolovat
      - Správnost a čitelnost kódu.
      - Dodržení konvencí a best practices.
      - Kvalitu komentářů a dokumentace.
      - Funkčnost nové funkce.
    - Diskuse
      - Recenzenti mohou prostřednictvím komentářů v PR navrhovat úpravy, klást otázky nebo doporučit změny.

7. Merge Pull Requestu:
    - Po schválení změn můžete provést `merge` Pull Requestu do hlavní větve.
    - Součení
      - Pokud se vyskytnou konflikty, je třeba je vyřešit.
    - Po sloučení změn
      - Aktualizujte svůj lokální repozitář (checkout).
      - můžete smazat větev s novou funkcí. 



## .gitignore

```
# Byte-compiled / optimized / DLL files
__pycache__/
*.py[cod]
*$py.class

# C extensions
*.so

# Distribution / packaging
.Python
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
wheels/
share/python-wheels/
*.egg-info/
.installed.cfg
*.egg
MANIFEST

# PyInstaller
#  Usually these files are written by a python script from a template
#  before PyInstaller builds the exe, so as to inject date/other infos into it.
*.manifest
*.spec

# Installer logs
pip-log.txt
pip-delete-this-directory.txt

# Unit test / coverage reports
htmlcov/
.tox/
.nox/
.coverage
.coverage.*
.cache
nosetests.xml
coverage.xml
*.cover
*.py,cover
.hypothesis/
.pytest_cache/
cover/

# Translations
*.mo
*.pot

# Django stuff:
*.log
local_settings.py
db.sqlite3
db.sqlite3-journal

# Flask stuff:
instance/
.webassets-cache

# Scrapy stuff:
.scrapy

# Sphinx documentation
docs/_build/

# PyBuilder
.pybuilder/
target/

# Jupyter Notebook
.ipynb_checkpoints

# IPython
profile_default/
ipython_config.py

# pyenv
#   For a library or package, you might want to ignore these files since the code is
#   intended to run in multiple environments; otherwise, check them in:
# .python-version

# pipenv
#   According to pypa/pipenv#598, it is recommended to include Pipfile.lock in version control.
#   However, in case of collaboration, if having platform-specific dependencies or dependencies
#   having no cross-platform support, pipenv may install dependencies that don't work, or not
#   install all needed dependencies.
#Pipfile.lock

# UV
#   Similar to Pipfile.lock, it is generally recommended to include uv.lock in version control.
#   This is especially recommended for binary packages to ensure reproducibility, and is more
#   commonly ignored for libraries.
#uv.lock

# poetry
#   Similar to Pipfile.lock, it is generally recommended to include poetry.lock in version control.
#   This is especially recommended for binary packages to ensure reproducibility, and is more
#   commonly ignored for libraries.
#   https://python-poetry.org/docs/basic-usage/#commit-your-poetrylock-file-to-version-control
#poetry.lock

# pdm
#   Similar to Pipfile.lock, it is generally recommended to include pdm.lock in version control.
#pdm.lock
#   pdm stores project-wide configurations in .pdm.toml, but it is recommended to not include it
#   in version control.
#   https://pdm.fming.dev/latest/usage/project/#working-with-version-control
.pdm.toml
.pdm-python
.pdm-build/

# PEP 582; used by e.g. github.com/David-OConnor/pyflow and github.com/pdm-project/pdm
__pypackages__/

# Celery stuff
celerybeat-schedule
celerybeat.pid

# SageMath parsed files
*.sage.py

# Environments
.env
.venv
env/
venv/
ENV/
env.bak/
venv.bak/

# Spyder project settings
.spyderproject
.spyproject

# Rope project settings
.ropeproject

# mkdocs documentation
/site

# mypy
.mypy_cache/
.dmypy.json
dmypy.json

# Pyre type checker
.pyre/

# pytype static type analyzer
.pytype/

# Cython debug symbols
cython_debug/

# PyCharm
#  JetBrains specific template is maintained in a separate JetBrains.gitignore that can
#  be found at https://github.com/github/gitignore/blob/main/Global/JetBrains.gitignore
#  and can be added to the global gitignore or merged into this file.  For a more nuclear
#  option (not recommended) you can uncomment the following to ignore the entire idea folder.
#.idea/

# Ruff stuff:
.ruff_cache/

# PyPI configuration file
.pypirc
```
