# Plant-Disease-Detection


```
- Upgrade pip with the mentioned command below.
```
pip install --upgrade pip
```
- Install requirements with the mentioned command below.
```
pip install -r requirements.txt
```
- Run the code with the mentioned command below.

streamlit run app.py 


The Error:
line 1144, in _update_config_with_toml parsed_config_file = toml.loads(raw_toml)

Solve :
https://stackoverflow.com/questions/59811357/how-to-solve-toml-decoder-tomldecodeerror-key-group-not-on-a-line-by-itself-l
