pipeline {
    agent any
    stages {
        
         stage('docker-credential') {
            steps {
            
                sh 'docker login -u arijhakouna -p arij12345'  
            }
        }
        
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
