pipeline {
   agent {label 'master'}
   stages {
      stage('Build') {
         steps {
             sh 'xelatex test.tex'
         }
      }
   }
}

