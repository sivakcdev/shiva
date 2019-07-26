pipeline {
	agent { label 'node1' }
	stages {
			stage('Build') {
				steps {
					sh 'mvn clean package'
			}
			stage('docker-build') {
				steps {
					sh 'docker build -t ubuntu/shiva:v2.0.0 .'
			}			
		
		}
	}
 }
