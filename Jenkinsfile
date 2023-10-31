pipeline {
    agent any

    stages {
        stage('Pull Souce Code') {
            steps {
                git branch: 'main', url: 'https://github.com/shahedcisa/comit-1'
            }
        }
        stage('Execute a command') {
            steps {
                echo 'Hello World!'
            }
        }
    }
}
