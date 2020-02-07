pipeline {
    agent { dockerfile true  }
    stages {
        stage('Test') {
            steps {
                echo 'Connecting ...'
                sh 'python --version'
            }
        }
    }
}
