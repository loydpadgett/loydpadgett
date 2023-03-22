pipeline {
    agent any

    stages {
        stage('list local folder contents') {
            steps {
                ls -lR
            }
        }
        stage('list proc info') {
            steps {
                'uname -a'
            }
        }
    }
}
