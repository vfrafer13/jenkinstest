pipeline {
  agent any
  stages {
    stage('vagrantfile') {
      steps {
        dir(path: '/home/chef-repo/vagrant')
        dir(path: '/home/chef-repo/vagrant') {
          sh 'vagrant up'
        }

      }
    }
  }
}