pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building static site...'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests... (dummy test)'
                sh 'echo "HTML & CSS syntax check passed!"'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying... (just printing deploy step for now)'
            }
        }
    }
}
