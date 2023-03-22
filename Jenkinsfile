pipeline {
    agent any

    stages {
        stage('list local folder contents') {
            steps {
                sh '''
                #!/bin/bash
                ls -lR
                '''
            }
        }
        stage('list proc info') {
            steps {
                sh '''
                #!/bin/bash
                uname -a
                '''
            }
        }
    }
}
