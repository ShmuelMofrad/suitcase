# Suitcase
## Bill of Material pom
suitcase is unus.one bill of material (BOM) pom. general settings for all dependencies unus.one's projects.

How to use it?
--------------
Start out by adding the parent configuration to your pom.
    
    <dependencyManagement>
		 <dependencies>
		  	 <dependency>
			 	 <groupId>one.unus</groupId>
				 <artifactId>suitcase</artifactId>
				 <version>0.0.1</version>
				 <type>pom</type>
				 <scope>import</scope>
		    </dependency>
	    </dependencies>
    </dependencyManagement>
    
    <dependencies>
	     <dependency>
	        <groupId>xxx.xxx.xxx</groupId>
	        <artifactId>xxx</artifactId>
	        <scope>compile</scope>
	     </dependency>
    </dependencies>