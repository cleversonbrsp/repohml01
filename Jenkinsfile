
pipeline {
    agent any

    stages {
        stage('Checkout Project Repository') {
            steps {
                // Check out the project repository
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], userRemoteConfigs: [[url: 'https://github.com/cleversonbrsp/repohml02.git']]])
            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
                // Add your build commands here
            }
        }

        stage('Test') {
            steps {
                echo "Testing the project..."
                // Add your test commands here
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the project..."
                // Add your deploy commands here
            }
        }
    }
}



// pipeline {
//     agent any

//     stages {
//         stage('Checkout Project Repository') {
//             steps {
//                 // Check out the project repository
//                 checkout([$class: 'GitSCM', branches: [[name: '*/master']], userRemoteConfigs: [[url: 'https://github.com/cleversonbrsp/repohml02.git']]])
//             }
//         }

//         stage('Build') {
//             steps {
//                 echo "Building the project..."
//                 // Add your build commands here
//             }
//         }

//         stage('Test') {
//             steps {
//                 echo "Testing the project..."
//                 // Add your test commands here
//             }
//         }

//         stage('Deploy') {
//             steps {
//                 echo "Deploying the project..."
//                 // Add your deploy commands here
//             }
//         }
//     }
// }



// pipeline {
//     agent any

//     stages {
//         stage('CHECKOUT DO REPOSITORIO DE ARQUIVOS') {
//             steps {
//                 checkout([$class: 'GitSCM', branches: [[name: '*/main']], userRemoteConfigs: [[url: 'https://github.com/cleversonbrsp/repohml02.git']]])
//             }
//         }

//         stage('BUILD') {
//             steps {
//                 echo "BUILDING..."
//             }
//         }

//         stage('TESTE') {
//             steps {
//                 echo "TESTANDO..."
//             }
//         }
//     }
// }
