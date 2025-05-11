pipeline {
    agent { label 'docker-agent-python' }

    stages {
        stage('Run Python') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}
