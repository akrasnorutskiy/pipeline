pipeline {
  agent any
    }
    stages {
      stage('Run Ansible') {
          steps {
              ansiblePlaybook playbook: 'main.yml', sudoUser: null
          }
      }
    }
}
