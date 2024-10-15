pipeline {
    agent any
    tools {
        maven 'M2_HOME'
    }
    stages {
        stage('GIT'){
            steps {
                git branch: 'master',
                url: 'https://github.com/boujelbenezaineb/time-sheet'
            }
        }

        stage('MVN CLEAN') {
            steps {
                sh 'mvn clean'
            }
        }
        stage('MVN COMPILE') {
            steps {
                sh 'mvn compile'
            }
        }

        stage ('MVN SONARQUBE') {
            steps {
                sh 'MVN SONARQUBE'
            }
        }
            
    }
}

