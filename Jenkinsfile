pipeline{
    agent any
    
    stages{
        stage ('git Checkout'){
            steps {
            gitCheckout
                (git branch: 'main', url: 'https://github.com/srinivas30240/mrdevops_java_app.git')
            }
        }
    }
}
