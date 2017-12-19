pipeline {
  agent {
    docker {
          image 'ubuntu:16.04'
      }
    }
    stages {
      stage('build') {
          steps {
              sh 'cd ~'
              sh 'ls -la'
              ansiblePlaybook playbook: 'main.yml', sudoUser: null
          }
      }
    }
}
