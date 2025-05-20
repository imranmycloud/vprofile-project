pipeline{

    agent any
    
    stages{
         
        stage('Git Checkout'){
                  
            steps{
                 script{
                    git branch: 'local', url: 'https://github.com/imranmycloud/vprofile-project.git'
                 }
            
            }
             
        }
    }
}
