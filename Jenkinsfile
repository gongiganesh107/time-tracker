pipeline {
        agent any
         stages {
              stage('Init') {
                   steps {
                        echo 'Jenkins code pipeline session '
                   }
              }                   
                   stage('Build') {
                   steps {
                        echo 'Bulding sample maven project '
                   }
              }
                stage('Deploy') {
                   steps {
                        echo 'Deploying in staging area  '
                   }
            }
              stage('Deploy in prodution') {
                   steps {
                        echo 'Deploying in production area  '
                   }
            }
              
              
       }
}
