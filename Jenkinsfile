pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
              ansiblePlaybook playbook: 'main.yml', sudoUser: null
            }
        }
    }
}
