# maven-archetype-msb

Maven archetype for MSB java microservices. 
Microservice structure is based on [BCE](http://epf.eclipse.org/wikis/openuppt/openup_basic/guidances/concepts/entity_control_boundary_pattern,_uF-QYEAhEdq_UJTvM1DM2Q.html) pattern

## How to use 

First of all you need to install this archetype into your local maven repository.
Clone the project from gihub and run ```mvn install```

Now you are ready to use it. 

```
	  mvn archetype:generate \
	  -DarchetypeGroupId=io.github.tcdl.maven.archetypes \
	  -DarchetypeArtifactId=msb-micro \
	  -DarchetypeVersion=1.0-alpha
```
