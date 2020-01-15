pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh sklearn_elasticnet_wine/train.py
            }
        }
    }
}
