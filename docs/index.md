# PDRO Ontology Documentation

[//]: # "This file is meant to be edited by the ontology maintainer."

Welcome to the PDRO documentation!

You can find descriptions of the standard ontology engineering workflows [here](odk-workflows/index.md).

## PDRO schema

[//]: # ![Screenshot](img/HEPRO.png)

## Classes

|IRI         |value                                         |def                                                                                                                                                                     |
|------------|----------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|PDRO_0000040|drug dispensing procedure                     |A healthcare procedure in which a specified quantity of a particular drug product is made available with the goal of the drug product being administered to an organism.|
|PDRO_0000041|drug dispensing record item                   |A data item that is part of a drug-dispensing record and describes how much of some drug products have been dispensed to a patient.                                     |
|PDRO_0000042|drug dispensing record                        |An information content entity that is usually part of a pharmacist information system and includes patient identification as well as drug dispensing record item.       |
|PDRO_0000109|drug product characterization                 |An information content entity that characterizes a class of drug product.                                                                                               |
|PDRO_0000110|drug dispensing record item dispensing date   |A process temporal characterization that is about a drug dispensing procedure.                                                                                          |
|PDRO_0000111|dispensed drug quantity                       |A data item that is about the total quantity of a drug product that was distributed during a drug dispensing procedure.                                                 |
|PDRO_0000112|drug dispensing covered duration specification|A directive information entity that specifies over how much time a dispensed drug quantity should be administered.                                                      |
|PDRO_0000114|drug dispensing total charge                  |The total amount charged by a healthcare organization to payers to cover a drug dispensing procedure and related drug products.                                         |
|PDRO_0000115|drug dispensing total payment                 |The total amount actually paid from all payers to cover a drug dispensing procedure and related drug products.                                                          |
|PDRO_0000116|drug dispensing drug product charge           |The amount paid by the payer to a pharmacy for the drug.                                                                                                                |
|PDRO_0000117|drug dispensing healthcare provider charge    |The amount paid by the Payer to a pharmacy for dispensing a drug.                                                                                                       |
