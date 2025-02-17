[![Smart Data Models](https://smartdatamodels.org/wp-content/uploads/2022/01/SmartDataModels_logo.png "Logo")](https://smartdatamodels.org)  

Smart Data Models 
==================

The [Smart Data Models](https://smartdatamodels.org) is a program lead by [4 organizations](https://smartdatamodels.org/index.php/faqs/) with the collaboration of [more than 70](https://smartdatamodels.org/index.php/statistics/) and open to collaboration. It provides multisector agile standardized free and open-licensed data models based either on actual use cases or on adopted open standards.
The data models describe the entities and their attributes to be used in digital twins deployments, data spaces and other smart applications. The data models are grouped in subjects. Each subject is available at a unique repository at [https://smart-data-models.github.com](https://smart-data-models.github.com). Contributions to existing data models can be done there. New ones are done in the [incubated repository](https://github.com/smart-data-models/incubated/tree/master) once [filled this form](https://smartdatamodels.org/index.php/new-incubated-data-models/) for getting the permissions. [This manual](https://bit.ly/contribution_manual) helps you with the creation.

This python package includes all the data models and several functions (listed below) to use them in your developments.

Every data model is open licensed and the list of its attributes and every attribute definition is included. Also, there is a function to check if a key values payload complies with a data model.  

If you want to be updated on this package you can join this [mailing list](https://smartdatamodels.org/index.php/developers-list/) (Announcements are sent only when something relevant happens). We love to hear from you at info@smartdatamodels.org

There are several online tools to manage and to create the data models, [generate examples](https://smartdatamodels.org/index.php/generate-a-ngsi-ld-keyvalues-payload-compliant-with-a-data-model/) or to adapt to [existing ontologies](https://smartdatamodels.org/index.php/generate-acontext-based-on-exter### nal-ontologies-iris/). See tools menu option at the [home site](https://smartdatamodels.org).

Currently, there are thirteen domains. 
### [Smart Cities](https://github.com/smart-data-models/SmartCities)
### [Smart Agrifood](https://smartdatamodels.org/index.php/statistics/)
### [Smart Water](https://github.com/smart-data-models/SmartWater)
### [Smart Energy](https://github.com/smart-data-models/SmartEnergy)
### [Smart Environment](https://github.com/smart-data-models/SmartEnvironment)
### [Smart Robotics](https://github.com/smart-data-models/SmartRobotics)
### [Smart Sensoring](https://github.com/smart-data-models/Smart-Sensoring)
### [Cross sector](https://github.com/smart-data-models/CrossSector)
### [Smart Aeronautics](https://github.com/smart-data-models/SmartAeronautics)
### [Smart Destination](https://github.com/smart-data-models/SmartDestination)
### [Smart Health](https://github.com/smart-data-models/SmartHealth)
### [Smart Manufacturing](https://github.com/smart-data-models/SmartManufacturing)
### [Smart Logistics](https://github.com/smart-data-models/SmartLogistics)

## Functions available include:

1- List all data models. Function list_all_datamodels()

2- List all subjects. Function list_all_subjects()

3- List the data models of a subject. Function datamodels_subject(subject)

4- List description of an attribute. Function description_attribute(subject, datamodel, attribute)

5- List data-type of an attribute. Function datatype_attribute(subject, datamodel, attribute)

6- Give reference model for an attribute. Function model_attribute(subject, datamodel, attribute)

7- Give reference units for an attribute. Function attributes_datamodel(subject, datamodel)

8- List the attributes of a data model. Function attributes_datamodel(subject, datamodel)

9- List the NGSI type (Property, Relationship or Geoproperty) of the attribute. Function ngsi_datatype_attribute(subject, datamodel, attribute)

10.- Validate a json schema of a data model. Function validate_data_model(schemaUrl)

11.- Print a list of data models attributes separated by a separator. Function print_datamodel(subject, datamodel, separator, meta_attributes)

## Pending features (glad to receive contributions to them)

A.- Function to update the data models to the last version. The official list of data models is here
[https://raw.githubusercontent.com/smart-data-models/data-models/master/specs/AllSubjects/official_list_data_models.json](https://raw.githubusercontent.com/smart-data-models/data-models/master/specs/AllSubjects/official_list_data_models.json)

B.- Function to update the database of attributes. The official database is here [https://smartdatamodels.org/extra/smartdatamodels.json](https://smartdatamodels.org/extra/smartdatamodels.json)

C.- Function to allow submission of improvements (i.e. missing recommended units or model) and comments to the different data models. Currently, you can do it searching for your data model here 
[https://smartdatamodels.org/index.php/list-of-data-models-3/](https://smartdatamodels.org/index.php/list-of-data-models-3/) going to the github repo and making your PR or raising your issues there.

D.- Function to submit a new data model to an incubation repository. Currently, this is done manually [incubated repository](https://github.com/smart-data-models/incubated/tree/master). By filling this [form](https://smartdatamodels.org/index.php/new-incubated-data-models/) you are granted to contribute with new data models. For existing data models just see point C    

if you want to suggest other functions / needs please let us know at info@smartdatamodels.org. 