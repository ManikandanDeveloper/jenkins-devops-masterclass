// Declarative pipeline
pipeline {
	// agent any
	agent { docker { image 'maven:3.6.3' } }
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
	}
	post {
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
