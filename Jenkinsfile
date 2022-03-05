pipeline {
	agent any
	stages{
	stage('Build') {
		steps{
		echo "Build"
		}
	}
	stage('Test') {
		steps{
		echo "Test"
		}
	}
		stage('Integration Test') {
			steps{
		echo "Integration Test"
			}
	}
	}
	post{
		always {
			echo "The job completed with"
		}
		success{echo "success"}
		failure {echo "failure"}
		
	}
	
}
