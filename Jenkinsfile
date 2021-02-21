pipeline {
    agent any

    tools {
        maven 'maven'
    }

    stages {
        stage ('build') {
            steps {
            sh 'mvn clean compile'
            }
        }
    stage ('test') {
           steps {
           sh 'mvn test'
           }
        }
    }
}