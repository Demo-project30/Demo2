pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'java -version'
            }
        }
        stage('Test'){
            steps {
                sh 'service nginx status'
            }
        }
        stage('Deploy') {
            steps {
                sh 'service jenkins status'
            }
        }
    }
}
