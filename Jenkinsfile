pipeline {

    agent any

    stages {

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
    }
}
