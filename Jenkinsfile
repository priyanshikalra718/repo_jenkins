pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                build job: 'samplebuildjob'
            }
        }
        stage('Test') {
            steps {
                build job: 'sampletestjob'
            }
        }
        stage('Release') {
            steps {
                build job: 'samplereleasejob'
            }
        }
        stage('Deploy') {
            steps {
                build job: 'sampledeployjob'
            }
        }
    }
}
