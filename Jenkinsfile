pipeline {
	agent any
	stages {
		stage("Build"){
			steps {
				echo "Building the application.."
			}
		}
		stage("Test"){
			steps{
				sh "python3 test.py"
			}
		}
	}
}
