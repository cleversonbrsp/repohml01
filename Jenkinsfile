pipeline {
    agent any

    stages {
        stage('Checkout Project Repository') {
            steps {
                // Check out the project repository without expecting a Jenkinsfile
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], userRemoteConfigs: [[url: 'https://github.com/cleversonbrsp/repohml02.git']]])
            }
        }

        stage('Build') {
            steps {
                echo "Building..."
                // Add your build commands here
            }
        }

        stage('Test') {
            steps {
                echo "Testing..."
                // Add your test commands here
            }
        }
    }
}
