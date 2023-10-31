pipeline {
    agent any

    stages {
        stage('Pull Souce Code') {
            steps {
                git branch: 'main', url: 'https://github.com/sambit81/Netflix-Homepage'
            }
        }
        stage('Execute a command') {
            steps {
                echo 'Hello World!'
            }
        }
    }
}
