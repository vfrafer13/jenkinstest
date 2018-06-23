pipeline {
  agent any
  stages {
    stage('vagrantfile') {
      steps {
        sh '''cd /home/chef-repo/vagrant
vagrant up'''
      }
    }
  }
}