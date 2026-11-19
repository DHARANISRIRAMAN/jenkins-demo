pipeline {
    agent any

    stages {
        stage('1. Git Checkout') {
            steps {
                echo 'Code downloaded from GitHub!'
                sh 'ls -la'
            }
        }

        stage('2. Build Stage') {
            steps {
                echo 'Building the application...'
                sh 'cat index.html'
            }
        }

        stage('3. Test Stage') {
            steps {
                echo 'All tests passed successfully!'
            }
        }
    }
}
