pipeline {
   agent any

   stages {
      stage('Deploy') {
         steps {
            git 'https://github.com/juberalam2k8/composetest.git'
            bat 'docker-compose up'
         }
      }
   }
}
