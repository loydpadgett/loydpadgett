pipeline {
    agent any

    stages {
        stage('list local folder contents') {
            steps {
                sh '''
                #!/bin/bash
                ls -lR && ls -l /
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
