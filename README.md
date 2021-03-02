# teched-dat265

[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/teched-dat265)](https://api.reuse.software/info/github.com/SAP-samples/teched-dat265)

### Description
This repository contains the results of various exercises in the SAP TechEd session DAT265.
So when you need to speed up you can download the solution and import it into EADesginer.

### Requirements
You need to have access to an SAP Enterprise Architecture Designer. SAP Enterprise Architecture Designer is an XSA application running on the SAP HANA XSA development stack. It allows for deployment on-premise as well as in the cloud. There are various availabilities of the product:
- SAP EA Designer as part of SAP HANA2 full use with 5 concurrent users included (unlimited "read" users)
- SAP EA Designer as part of SAP HANA2 Express with a 1 concurrent user included (unlimited "read" users)
- SAP EA Designer CE (Cloud Edition) 

### Download and Installation
1. You should download this repository and unpack it.
1. The files from the single sections can be imported into SAP EADesigner using the import function in the **Browse** mode.

### Known Issues
older version of SAP EADesigner do had a faulty generation of associations. Make sure relation columns are in the form
 - correct  "targettable_1" "targettable"   the generator of older version do the 
 - false  "targettable"   "targettable"   need to be manual adjusted
it is not allowed to have the same name for column and join

### License
Copyright (c) 2018 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
