pipeline {
	agent { label 'node1' }
	stages {
			stage('Build') {
				steps {
					sh 'mvn clean package'
			}
		
		}
	}
 }
