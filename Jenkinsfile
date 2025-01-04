pipeline{
	agent any 
	environment {
		VALUE = 'who'
	}
	stages {
		stage('build') {
			steps {
				echo "${VALUE}" | sh 
			}
		}
	}
}
