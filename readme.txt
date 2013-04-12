Running a Jar file from the other team
1) Download the other team's jar file into your project directory. 
2) Change your build.xml file line 131 from: 
    <target name="run-jar" depends="jar"> to 
    <target name="run-jar" depends="">
    And save it.
3) Execute command: ant run-jar
