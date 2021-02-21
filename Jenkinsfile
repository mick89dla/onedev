pipeline {
    agent any

    tools {
        maven 'maven'
    }

    stage ('test') {
           steps {
           sh 'mvn test'
           }
        }
    }
}