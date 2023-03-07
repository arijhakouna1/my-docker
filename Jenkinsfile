pipeline {
    agent any
    stages {
        stage('Build') {
            agent {
                docker {
                    image 'hello-word'

                }
            }
            steps {
                sh 'docker run hello-world'
                echo "I'm working"
            }
        }
    }
}
