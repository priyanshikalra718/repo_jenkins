pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Triggering Sample Build Job...'
                build job: 'samplebuildjob'
            }
        }
        stage('Test') {
            steps {
                echo 'Triggering Sample Test Job...'
                build job: 'sampletestjob'
            }
        }
        stage('Release') {
            steps {
                echo 'Triggering Sample Release Job...'
                build job: 'samplereleasejob'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Triggering Sample Deploy Job...'
                build job: 'sampledeployjob'
            }
        }
    }
}
