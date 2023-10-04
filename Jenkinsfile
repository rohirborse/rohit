pipeline {
    agent any

    stages {
        stage('Print Time and Date') {
            steps {
                timestamps { // This step captures timestamps
                    script {
                        sh date
                    }
                }
            }
        }
    }
