@library('roboshot-sharedlibrary') _
pipeline {
       agent {
        label 'WS'
    }
    options {
        // Timeout counter starts AFTER agent is allocated
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('Example') {
            steps {
                script{
                    sample.info("sample message")
                }
                echo 'Hello World'
            }
        }
    }
}