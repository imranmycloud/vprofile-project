@Library('my-shared-library') _

pipeline{

    agent any
    
    stages{
         
        stage('Git Checkout'){
                  
            steps{
                 script{
                     gitCheckout(
                     branch: "local",
                     url: "https://github.com/imranmycloud/vprofile-project.git"
                    )
                  
                }
            
            }
             
        }
         stage('Unit Test maven'){
                  
            steps{
                 script{
                     
                   mvnTest()
                }
            
            }
             
        }
    }
}
