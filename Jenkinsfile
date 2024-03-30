@Library('my-shared-library') _
pipeline{
    agent any
    
    stages{
        stage ('git Checkout'){
            steps {
            gitCheckout(
                branch: 'main', 
                url: 'https://github.com/srinivas30240/mrdevops_java_app.git'
                )
            }
        }

        stage ('unit test maven'){
            steps {
               script{
                  mvnTest() 
               }
            }
        }
    
}
