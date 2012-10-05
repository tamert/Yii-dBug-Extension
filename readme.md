 * YII FRAMEWORK - dBug Extension 
 *
 * SETUP
 * =============
 * this dBug folder copy 
 * yourproject/protected/extension/ here paste
 *
 * RUN Controller
 * =============
 * $this->widget('ext.dBug.dBug', array("item"=> variable [,forceType] ));
 * $this->widget('ext.dBug.dBug', array("item"=> $myVariable ));


Outputs colored and structured tabular variable information.
Variable types supported are: Arrays, Classes/Objects, Database and XML Resources.
Ability to force certain types of output. Example: You can force an object variable to be outputted as an array type variable.
Stylesheet can be easily edited.
Table cells can be expanded and collapsed