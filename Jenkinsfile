pipeline {
    agent any
    tools {
        maven 'maven' 
    }
    stages {
        stage('buildstage') {
            steps {
                mvn clean install
            }
        }
    }
}

