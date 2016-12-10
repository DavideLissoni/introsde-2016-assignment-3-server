# introsde-2016-assignment-3-server
Introsde-2016-assignment-3 readme
Davide Lissoni Mat.179878
11/12/2016


## 1.Introduction:

This readme is about the server part of the third assignment of the Introduction to Service Design and Engineering
course. The requirements was to develope a project similar to the assignment 2 by using SOAP services.

Server url:
Service WSDL url:

## 2.Implementation:
The server structure and the database maintain more or less the same structure used for the laboratory and for the assignment 2 as well since the assignment requirements refers to the laboratory exercises.

The server is structured in 4 different packages:

introsde.document.dao:
This package contains the class LifeCoachDao.java, class used in order to connect the project model to the database.

introsde.document.endpoint:
This package contains the class PeoplPublisher.java, class responsable to set the URL where the service can be accessed by a client application.

introsde.document.model:this package contains the entity classes(java EE component that represents the persistent data maintained in the database lifecoach.sqlite used in this project). The classes contain also method used to run database operations.
The classes are:

1.HealthMeasureHistory.java: refers to the database table HealthMeasureHistory;
2.HealthProfile.java: refers to the database table HealthProfile;
3.MeasureDefinition: refers to the database table MeasureDefinition;
4.Person: refers to the database table Person.

introsde.document.ws


