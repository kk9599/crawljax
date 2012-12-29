Crawljax Maven Archtypes
========================

Crawljax Plugin
---------------

To generate a plugin project template using Maven:

     mvn archetype:generate \
       -DarchetypeGroupId=com.crawljax.plugins.archetypes \
       -DarchetypeArtifactId=crawljax-plugins-archetype \
       -DarchetypeVersion=1.2 \
       -DgroupId=sample \
       -DartifactId=sample-plugin \

       
You can change the values of ``-DgroupId`` and ``-DartifactId`` to reflect your project's package and name. 
