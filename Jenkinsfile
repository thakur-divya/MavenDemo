pipeline {
    agent any

    tools {
        maven 'Maven'
        jdk 'JDK-21'
    }

    stages {
        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }
    }
}
