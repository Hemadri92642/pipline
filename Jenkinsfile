pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'git to checkout code to local repositery'
            }
        }
        stage('dev') {
            steps {
                echo 'deploy codeing to dev'
            }
        }
        stage('QA') {
            steps {
                echo 'git to checkot to qa'
            }
        }
        stage('Alpha') {
            steps {
                echo 'git to alpha'
            }
        }
        stage('prod') {
            steps {
                echo 'git to prod'
            }
        }
        stage('Deployement sucessful') {
            steps {
                echo 'All enveranments sucessful'
            }
        }
    }
}

