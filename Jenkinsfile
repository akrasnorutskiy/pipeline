pipeline {
  agent {
    docker {
          image 'python'
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
