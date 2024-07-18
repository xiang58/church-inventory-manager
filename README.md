# church-inventory-manager
* Create a virtual env
```
python3 -m venv .venv
```

* Activate virtual env
```
source .venv/bin/activate
```

* Confirm the venv is activated
```
which python
```

* Install required libraries
```
pip install -r requirements.txt
```

* Start app locally
```
streamlit run src/app.py
```

* Deactivate the venv
```
deactivate
```

* Turn on headers and column mode for SQLite
```
sqlite3 church_inventory.db -header -column
```

* Reference: 
    - https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/
    - https://docs.streamlit.io/
