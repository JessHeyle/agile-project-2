pipeline {
  agent any
  stages {
    stage('Run Shell Script') {
      steps {
        sh '''echo "Hello World"
echo $(date +%F)
echo $user
whoami'''
      }
    }
  }
}