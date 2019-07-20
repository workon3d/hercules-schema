# hercules-schema
Published Hercules Schema Repo

#### For each environments, Hercules schema json will be stored at each directories 
- e.g. ````./development````, ````./staging````, ````./production````

#### For the different version combinations, they will be managed with git branch.
- Brach naming rule: ````"{datamodel_ver.name}-{firmware_ver.name}-{mtconnect_ver.name}".gsub(/\s+/, '_')````

#### For each printer models, they will be generated as the seperated json file.
- File naming rule: ````{device.alias}-{model}-{submodel}.json````, e.g. mjp2500-20000-0.json

#### For Direct download
````https://raw.githubusercontent.com/workon3d/hercules-schema/{branch name}/{envrionment}/{filename}````
- e.g. https://raw.githubusercontent.com/workon3d/hercules-schema/v0.1-v0.1-1.4/development/mjp2500-20000-0.json
