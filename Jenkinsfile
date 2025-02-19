pipeline { 
    agent any

    stages {

        stage('Clone Repository') {

            steps {

                git 'https://github.com/arjunkoppineni/jen-demo.git'

            }

        }

        stage('Build') {

            steps {

                sh 'echo "Building the application..."'

            }

        }

        stage('Test') {

            steps {

                sh 'echo "Running tests..."'

            }

        }

        stage('Deploy') {

            steps {

                sh 'echo "Deploying application..."'

            } 

        } 
    }

}
