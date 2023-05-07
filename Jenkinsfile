pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello'
                sleep 5
            }
        }
         stage('build') {
            steps {
                echo 'Build'
                sleep 4
            }
        }
         stage('test') {
            steps {
                echo 'Test'
                sleep 3
            }
        }
         stage('deploy') {
            steps {
                echo 'Deploy'
            }
        }
    }
}
