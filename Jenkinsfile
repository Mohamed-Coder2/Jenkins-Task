pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/Mohamed-Coder2/Jenkins-Task'
            }
        }
        stage('Execute Bash Script') {
            steps {
                sh './script.sh'
            }
        }
    }
}
