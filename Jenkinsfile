pipeline {
      agent {label 'linux'}
      stages {
        stage('checkout'){
          steps{
          git 'https://github.com/TimberHash/Firstone.git'
          }
        }
        stage('compile'){
         steps {
          sh 'gcc example.c -o example'
         }
        }
      }
    }
    

