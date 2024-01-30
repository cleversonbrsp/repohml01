pipeline {
    agent any

    stages {
        stage('CHECKOUT DO REPOSITORIO DE ARQUIVOS') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], userRemoteConfigs: [[url: 'https://github.com/cleversonbrsp/repohml02.git']]])
            }
        }

        stage('BUILD') {
            steps {
                echo "BUILDING..."
            }
        }

        stage('TESTE') {
            steps {
                echo "TESTANDO..."
            }
        }
    }
}
