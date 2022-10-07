pipeline {
	agent any
	stages {
		stage('build') {
			steps {
				sh 'docker build -t belajar-pipeline .'
			}
		}
		stage('run') {
			steps {
				sh 'docker run --name belajar-pipeline -d -p 5000:80 belajar-pipeline'
			}
		}
	}
}
