pipeline{
	agent any 
	environment {
		VALUE = 'who'
	}
	stages {
		stage('build') {
			steps {
				echo 'First step'
				echo "${VALUE}" | sh 
			}
		}
	}
}
