pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/paulphilip/pythoncode.git'
            }
        }

        stage('Run Python Script') {
            steps {
                sh 'python3 test.py'
            }
        }
    }
}
