pipeline {
	agent { docker { image 'maven:3.6.3'}}
	stages{

		stage('Build') {
			steps{
					// sh 'mvn --version'
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

