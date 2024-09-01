#!groovy
//run docker build

properties([disableConcurrentBuilds()])

pipeline {
    agent any
	
	stages{
        stage('Build Docker Image') {
            steps {
                echo "================= start building image ==================="
				dir ('docker')
                    sh 'docker build . '
                }
            }
        }
    }
