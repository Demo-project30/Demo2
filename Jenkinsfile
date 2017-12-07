pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'mkdir test'
            }
        }
        stage('Test'){
            steps {
                sh 'cd test'
            }
        }
        stage('Deploy') {
            steps {
                sh 'cd ..'
            }
        }
    }
}
