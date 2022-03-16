# fr.prix-carburants:
Collect gaz station information from https://www.prix-carburants.gouv.fr/ website.

Used to export data as json to be used on [prixcarburants](https://github.com/floman321/prixcarburants) plugin for Jeedom.

# How to use:
Run the following command to collect station of all departments  
```python
python stations.py
```
Or
```python
python3 stations.py
```
JSON files will be created on the folder `listestations`, one per department.
## Command options:
- `-d` or `--departement` followed by department number (2 figures required) to collect data of this particular department. For example `-d 05` or `-d 2A`.
- `-l` or `--log` to write logs on a text file.

# Acknowledgment:
[cquest](https://github.com/cquest) for it's initial work on [datasources repository](https://github.com/openeventdatabase/datasources/tree/master/fr.prix-carburants) which is the source of this code.