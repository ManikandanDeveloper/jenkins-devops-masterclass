// Declarative pipeline
pipeline {
	agent any
	stages {
		stage ('Build') {
			steps {
				echo "Build Step"				
			}
		}
		stage ('Test') {
			steps {
				echo "Test Step"				
			}
		}
		stage ('Integration Test') {
			steps {
				echo "Integration Test Step"				
			}
		}
	} post {
		always {
			echo "Runs always"
		}
		success {
			echo "Runs on success"
		}
		failure {
			echo "Runs on failure"
		}
	}
}
