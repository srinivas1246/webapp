pipeline {
    agent any
    tools {
        maven 'Maven' 
    }
    stages {
        stage('buildstage') {
            steps {
                mvn clean install
            }
        }
    }
}

