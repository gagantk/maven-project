pipeline {
    agent any
    tools {
        maven 'localMaven'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                bat script: 'mvn clean package'
            }
        }
    }
}