pipeline {
  agent any
  stages {
    stage('vagrantfile') {
      steps {
        dir(path: '/home/chef-repo/vagrant') {
          fileExists '/home/chef-repo/vagrant/VagrantFile'
          sh 'vagrant up'
        }

      }
    }
  }
}