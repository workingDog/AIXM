AIXM
====

AIXM xsd files from [Eurocontrol](http://www.aixm.aero/public/subsite_homepage/homepage.html).

Attempts to compile AIXM into scala classes using [scalaxb](http://scalaxb.org/).

    mvn generate-sources

generates the scala source files.
 
However 
 
    mvn compile 
    
does not compile, it complains about duplicate names.
 