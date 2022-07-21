# jcoJars
Executable Jco-framework java jars.  
The code has been compiled with Java 1.8 compiler.


## Folder Content
| File/Folder | Description |  
| ----------- | ----------- |  
| _jcoql-engine-1.0.4.jar_ | Module to launch the _Jco-Engine_ |  
| _jcoql-ui-1.0.0.jar_ | Module to lauch the Jco-User-Interface (_Jco-UI_). Needs _Jco-Engine_ to run properly |  
| _jcoql-ds-server-1.0.0.jar_ | Module to launch _Jco-DS-Server_ |  
| _jcoql-ds-client-1.0.0.jar_ | Module to launch _Jco-DS-Client_. Need _Jco-DS-Server_ to run properly |  
| Folder _'config'_ | Advanced settings for _Jco-Engine_ |  
| Folder _'data'_ | Sample of data repository for _Jco-DS-Server_ |  
| Folders _'jcoql-engine'_, _'jcoql-ds-client'_, _'jcoql-ds-server'_ | Contain support libraries |  


## Deployment
Download the content of this repository on your computer.  
Launch the proper java jar to activate the desidered module.


## Script Shortcuts
The following batch script are devoloped for Windows operating systems.
| Script | Description | Parameters |   
| ------ | ----------- | ---- |   
| _jarLauncher.bat_ | Shortcut script to lauch the Jco modules | _01_: to launch _Jco-DS-Server_ |  
| | | _02_: to launch _Jco-DS-Client_ |  
| | | _03_: to launch _Jco-Engine_ |  
| | | _04_: to launch _Jco-UI_ |   
| _jcoLauncher.bat_ | Shortcut script to launch _all_ Jco modules| |  
| _uiLauncher.bat_ | Shortcut script to launch only _Jco-Engine_ and _Jco-UI_ | |   
| _dsLauncher.bat_ | Shortcut script to launch only _Jco-DS_Server_ and _Jco-DS_Client_ | |   

## Advanced Settings
In the folder [./config/settings.properties](./config/settings.properties) is possible to set advanced parameters for _Jco-Engine_ and _Jco-DS_:
| Parameter | Description | Default value |  
| --------- | ----------- | ------ |  
| _nProcessors_ | Number of processors to use in the hosting machine | _4_ |   
| _server.data-path_ | Location  of the _Jco Engine_ repository folder | _./data_ |  
| _server.port_ | Communication port for _Jco-DS_ communication | _17017_ |  

