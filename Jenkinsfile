pipeline {
    agent { docker 'python:3.5.1' } 
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                sh 'whoami'
            }
        }
    }
}
