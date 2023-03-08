pipeline {
     agent { dockerfile true }
    stages {
        
      /*   stage('docker-credential') {
            steps {
            
                sh 'docker login -u arijhakouna -p arij12345'  
            }
        }*/
        
        stage('Build') {
          
        
        
            steps {
                sh 'docker run hello-world'
                echo "I'm working"
            }
        }
        
        
       
    }
}
