pipeline {
    agent any  // Specifies where the pipeline will run (e.g., any available agent)

    stages {
        stage('Build') {
            steps {
                // Commands to execute during the Build stage
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                // Commands to execute during the Test stage
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                // Commands to execute during the Deploy stage
                echo 'Deploying...'
            }
        }
    }
    post {
        always {
            // Actions to perform after all stages have run
            echo 'Pipeline completed.'
        }
        success {
            // Actions to perform if the pipeline is successful
            echo 'Pipeline succeeded!'
        }
        failure {
            // Actions to perform if the pipeline fails
            echo 'Pipeline failed!'
        }
    }
}
