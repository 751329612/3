pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'start build!'
                python 'manage.py'
            }
        }
        stage('Test') {
            steps {
                echo 'start test!'
            }
        }
    }
}
