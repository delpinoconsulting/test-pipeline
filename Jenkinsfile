pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'sh \'/opt/jenkins/packer validate /opt/jenkins/packer.json\''
      }
    }
  }
}