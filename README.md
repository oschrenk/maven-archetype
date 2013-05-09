# README #

A maven archetype with up-to-date plugins and dependencies for my needs

	git clone git clone git@github.com:oschrenk/maven-archetype.git
	cd maven-archetype
	mvn clean install

Create a new project

	cd $HOME/Projects
	mvn archetype:generate -DarchetypeGroupId=com.oschrenk.maven -DarchetypeArtifactId=default-archetype -DarchetypeVersion=1.0-SNAPSHOT