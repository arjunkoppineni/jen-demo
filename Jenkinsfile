pipeline { 
    agent any

    stages {

        stage('Clone Repository') {

            steps {

                git url:'https://github.com/arjunkoppineni/jen-demo.git', branch:'main'

            }

        }

        stage('Build') {

            steps {

                sh 'echo "Building the application..."'
                sh 'script.py'

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
