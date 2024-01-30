pipeline {
    agent any

    stages {
        stage('Checkout do repositório secundario') {
            steps {
                // Check out the project repository "repohml02.git"
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], userRemoteConfigs: [[url: 'https://github.com/cleversonbrsp/repohml02.git']]])
            }
        }

        stage('Build') {
            steps {
                echo "Building do projeto."
                // Add your build commands here
            }
        }

        stage('Test') {
            steps {
                echo "Testando o projeto"
                // Add your test commands here
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy do projeto"
                // Add your deploy commands here
            }
        }
    }
}
