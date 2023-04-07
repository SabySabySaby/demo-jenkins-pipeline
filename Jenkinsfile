pipeline {
    agent any 
    
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building feacture-01 branch..."'
            }
        }
        
        stage('Test') {
            steps {
                sh 'echo "Testing feacture-01 branch..."'
            }
        }
        
        stage('Deploy') {
            steps {
                sh 'echo "Deploying testing branch..."'
            }
        }
    }
}
