pipeline {
    agent any
    triggers {
        pollSCM '*/5 * * * *'
    }
    stages {
        stage('Build') {
            steps {
                script {
                    echo 'Building on the master node'
                    // Add your build steps here
                }
            }
        }

        stage('Test') {
            steps {
                script {
                    echo 'Testing on the master node'
                    // Add your test steps here
                }
            }
        }

        // Add more stages as needed
    }
}
