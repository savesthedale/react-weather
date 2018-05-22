pipeline {
    agent {
        node {
            label 'testing'            
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'sudo npm install --allow-root' 
            }
        }
    }
}
