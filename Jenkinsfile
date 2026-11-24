
pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/bmejri988-spec/Timesheet-DevOps-Jenkins'
            }
        }

        stage('Compile') {
            steps {
                sh 'mvn compile'
            }
        }
    }
}

