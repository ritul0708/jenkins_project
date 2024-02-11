pipeline {
	agent any 
	tools {
		maven MAVEN_HOME
	}
	stages {
		stage('Welcome Stage') {
			steps {
				echo 'welcome to jenkins pipeline'
			}
		}
		
		stage('Maven Clean') {
			steps {
				sh 'mvn clean'
			}
		}
		
		stage('Maven Build') {
			steps {
				sh 'mvn build'
			}
		}
		
		stage('Last Stage') {
			steps {
				echo 'Success !!!'
			}
		}
	}
}
		
