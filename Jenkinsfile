pipeline {

    agent any

    tools {

        maven 'Maven 3.8.4'

        jdk 'openjdk'

    }

    stages {

        stage('Build') {

            steps {

                sh "mvn compile"

            }

        }

        stage('Test') {

            steps {

                sh "mvn test"

            }

        }

    }

}
