pipeline {
    agent any
    tools {
        maven 'Maven' 
    }
    stages {
        stage('buildstage') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}

