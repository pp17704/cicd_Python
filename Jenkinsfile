pipeline {
    agent any
      stages {
        stage('Build') {
            steps {
                sh 'docker build -t myapp:latest .'
            }
        }

        stage('Test') {
            steps {
                sh 'python app.py'
            }
        }

        stage('Deploy'){
            steps {
                sh 'echo Deployment simulates'
            }
        }
      }
}