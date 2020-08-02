pipeline {
    agent any 
	
    stages {
        stage('Build') { 
            steps {
                echo "Build"
				bat label: '', script: 'git --version'
            }
        }
        stage('Test') { 
            steps {
                echo "testing"
               bat label: '', script: 'java -version'
                }
        }
        stage('Deploy') { 
            steps {
                echo "Deployment"
                bat label: '', script: 'git clone https://github.com/raghwendra-sonu/Jenkins_Pipeline_Demo.git'
				 
            }
        }
    }
	
}
_
