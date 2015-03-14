# gwt:shell #

## Mojo Attributes : ##

  * Requires a Maven 2.0 project to execute.
  * Requires dependency resolution of artifacts in scope: runtime

## Required Parameters ##

|**Name**|**Type**|**Description**|
|:-------|:-------|:--------------|
|gwtHome|String|No description.|

## Optional Parameters ##

|**Name**|**Type**|**Description**|
|:-------|:-------|:--------------|
|debug|boolean|No description. Default value is true.|
|debugPort|String|No description. Default value is 5005.|
|gwtApp|String|The GWT application to be excuted. Specified as the full qualified name of the gwt.xml file, leaving out the double extention (.gwt.xml). If this variable is left unset, the plugin will search through the classpath to find all applications.|
|gwtStyle|String|Script output style: OBF[USCATED](USCATED.md), PRETTY, or DETAILED (defaults to OBF) Default value is obf.|
|jvmArgs|List|No description.|
|logLevel|String|The level of logging detail: ERROR, WARN, INFO, TRACE, DEBUG, SPAM, or ALL Default value is WARN.|
|outputDirectory|String|Directory were the compiled class should be placed Default value is ${basedir}/target/${project.build.finalName}.|
|skip|boolean|No description. Default value is false.|
## Parameter Details ##

### debug ###

No Description.

  * Type : boolean
  * Required : No
  * Expression : ${gwt.debug}
  * Default : true

### debugPort ###

No Description.

  * Type : java.lang.String
  * Required : No
  * Expression : ${gwt.debug.port}
  * Default : 5005

### gwtApp ###

The GWT application to be excuted. Specified as the full qualified name of the gwt.xml file, leaving out the double extention (.gwt.xml).

If this variable is left unset, the plugin will search through the classpath to find all applications.

  * Type : java.lang.String
  * Required : No
  * Expression : ${gwt.app}

### gwtHome ###

No Description.

  * Type : java.lang.String
  * Required : Yes
  * Expression : ${gwt.home}

### gwtStyle ###

Script output style: OBF[USCATED](USCATED.md), PRETTY, or DETAILED (defaults to OBF)

  * Type : java.lang.String
  * Required : No
  * Expression : ${gwt.style}
  * Default : obf

### jvmArgs ###

No Description.

  * Type : java.util.List
  * Required : No

### logLevel ###

The level of logging detail: ERROR, WARN, INFO, TRACE, DEBUG, SPAM, or ALL

  * Type : java.lang.String
  * Required : No
  * Expression : ${gwt.logLevel}
  * Default : WARN

### outputDirectory ###

Directory were the compiled class should be placed

  * Type : java.lang.String
  * Required : No
  * Expression : ${gwt.outputDirectory}
  * Default : ${basedir}/target/${project.build.finalName}

### skip ###

No Description.

  * Type : boolean
  * Required : No
  * Expression : ${gwt.skip}
  * Default : false