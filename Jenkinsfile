pipeline {
    agent any
	
	stages{
        stage('Build Docker Image') {
            steps {
		    dir ('docker')
                    sh 'docker build . '
                }
            }
        }
    }
