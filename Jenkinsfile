pipeline {

    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Cloning Repository'
            }
        }

        stage('Build') {
            steps {
                sh './gradlew build'
            }
        }

        stage('Run') {
            steps {
                sh './gradlew run'
            }
        }

        stage('Test') {
            steps {
                sh './gradlew test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Gradle Deployment Successful'
            }
        }
    }
}
