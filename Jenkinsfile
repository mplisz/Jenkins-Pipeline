pipeline {
     agent any
     stages {
         stage('Build') {
             steps {
                 sh 'echo "Hello World - it is Jenkins course"'
                 sh '''
                     echo "Multiline shell steps works too"
                     ls -lah
                 '''
             }
         }
       }
    }
