pipeline {
	agent any
	stages {
		stage("Cleaning Stage") {
			steps {
			       bat "mvn clean"
			 }
				     
		}
		stage("Testing Stage") {
			steps {
			       bat "mvn test"
			 }
		}
		stage("Patching Stage") {
			steps {
			       bat "mvn package"
			 }
		}
	}
}
