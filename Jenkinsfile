pipeline {
    agent any

    stages {
        stage('Print Time and Date') {
            steps {
                timestamps { // This step captures timestamps
                    script {
                        def currentDate = new Date()
                        echo "Current Date and Time: ${currentDate}"
                    }
                }
            }
        }
    }
