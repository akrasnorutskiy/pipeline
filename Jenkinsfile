pipeline {
  agent {
    docker {
          image 'ubuntu:16.04'
      }
    }
    stages {
        stage('test'){
          steps{
            ansiblePlaybook playbook: 'main.yml', sudoUser: null
          }
        }
        stage('build') {
            steps {
                sh 'cd ~'
		            sh 'ls -la'
            }
        }
    }
}
