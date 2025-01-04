pipeline{
	agent any 
	stages {
		stage('build') {
			steps {
				echo 'First step'
				sh 'who'
			}
		}
		stage('test') {
			steps {
				echo 'second step'
				sh 'pwd'
			}
		}
		stage('deploy') {
			steps {
				echo 'Last step'
				sh 'uname'
			}
		}
	}
}
