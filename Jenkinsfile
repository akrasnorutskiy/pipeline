pipeline {
    stages {
      stage('run Ansible') {
          steps {
              ansiblePlaybook playbook: 'main.yml', sudoUser: null
          }
      }
    }
}
