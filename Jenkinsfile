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

        stage ('MVN CLEAN') {
            steps {
                sh '.............'
            }
        }

        stage ('MVN COMPILE') {
            steps {
                sh '...............'
                    }
        }

        stage ('MVN SONARQUBE') {
            steps {
                sh '.........'
            }
        }
            
    }
}

