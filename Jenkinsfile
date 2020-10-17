pipeline {
   agent any
   environment {
       color = "blue"
   }
   stages {
       stage('first') {
            agent { label 'master' }
            steps {
               sh "printenv | sort"
            }
        }
    }
}
 
