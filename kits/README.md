TEIID UDF Arche Type
================

This maven project is use to create the TEIID UDF archetype, which then can be used to generate a new java project.

When the udf project is generated, you will end up with the following structure:

-  ${udf_artifactID}
	|-	kits
		|-	wildfly
			|-	cli-scripts
				|-	add-module-__udf-name__.cli
			|-	modules
				|-	flipkart5
					|-	main
						|-	module.xml
		|-	wildfly-dist.xml 
	| -	pom.xml
	| -	src
		|-	main
			|-	java
				|-	flipkart5
					|-	__udf-name__.java


