pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Etape Build en cours...'
                sh 'echo "Compilation du projet"'
                sh 'sleep 3'
            }
        }
        stage('Test') {
            steps {
                echo 'Etape Test en cours...'
                sh 'echo "Execution des tests"'
                sh 'sleep 2'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Etape Deploy en cours...'
                sh 'echo "Deploiement termine"'
            }
        }
    }
}
