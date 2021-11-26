pipeline {
	// agent { docker { image 'maven:3.6.3'} }

	agent any

	environement {
		dockerHome = tool 'myDocker'
		mavenHome = tool 'myMaven'
		PATH = "$dockerHome/bin:$mavenHome/bin:$PATH"
	}
	stages{
		stage('Build') {
			steps{
					sh 'mvn --version'
					sh 'docker version'
					echo "Build1"
					echo "Build2"
			}
		}


		stage('Test') {
			steps{
					echo "Test1"
					echo "Test2"
				}
		}


		stage('Integration Test') {
			steps{
					echo "IT1"
					echo "IT2"
				}
		}
	
	
	}
	
}

