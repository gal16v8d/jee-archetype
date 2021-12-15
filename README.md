# JEE Archetype
This folder contains a base JEE7 project structure.

## Getting started
### Prerequisites
* Git
* Maven

### How to use
For make changes in the archetype structure please check src\main\resources\archetype-resources folder, inside is the project structure,
also on src\main\resources\META-INF\maven you will find the metadata file, for modify the entries in structure if you need that.

After make the changes you can install it locally using -> **mvn clean install** command.

For generate a base project using the archetype you can use a command like this:
**mvn archetype:generate -DarchetypeGroupId=com.gsdd -DarchetypeArtifactId=jee7 -DarchetypeVersion=1.0.003 -DgroupId=your_group_id -DartifactId=your_artifact_id**

## Contributors

* **Alexander Galvis Grisales** - *Initial setup*