pipeline {
    agent {label 'node'}
    stages {
        stage('Build') { 
            steps {
                git 'https://github.com/satish143/apache-playbook.git'
            }
        }
        stage('Test') { 
            steps {
                echo "ramesh"
            }
        }
        stage('Deploy') { 
            steps {
                echo "nani"
            }
        }
    }
}
