Pipeline {
   agent any
   tools {
     maven "maven3.9.6"  
   }
   stages {
       stage('Git Checkout') {
            steps {
            script{
                git branch: 'dev', url: 'https://github.com/papunabiswal/mrsoft_dev_backend.git' 
                }  
            }
        }
   }
}
