# Evidence of the use of the MVC architecture


MVC is a style of software architecture that separates data from an application, user interface and control logic into three components.


M - Model: contains a representation of the data handled by the system
V - View: Information sent to the customer
C - Controller - Intermediate between Model and View



For the case of our project we interpret it as follows:



- M are all the classes created in the packages classes and classsAssisted
- V is the interface of the Discord text channel.
- C is the main code 'main'. In particular it would be the client event on_message. It is with this event that you control what is displayed and organizes the necessary steps for the classes (the model) to obtain the necessary data.
