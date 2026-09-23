pipeline {
    agent any

    stages {
        stage('Checkout Git') {
            steps {
                dir('/var/lib/jenkins/assignment1') {
                    git branch: 'develop',
                        url: 'https://github.com/Ramya29937/JenkinsAssignment1.git'
                }
            }
        }

        stage('Verify Files') {
            steps {
                dir('/var/lib/jenkins/assignment1') {
                    sh 'pwd'
                    sh 'ls -la'
                }
            }
        }
    }
}