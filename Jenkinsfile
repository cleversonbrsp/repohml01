pipeline {
    agent any

    stages {
        stage('Checkout do repositório secundario') {
            steps {
                // Checkout do repositório secundário
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], userRemoteConfigs: [[url: 'https://github.com/cleversonbrsp/repohml02.git']]])
            }
        }

        stage('Build') {
            steps {
                echo "Building do projeto."
                // Script Build aqui
            }
        }

        stage('Test') {
            steps {
                echo "Testando o projeto"
                // Script de teste aqui
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy do projeto"
                // Script do projeto aqui
            }
        }
    }
}
