pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Git-check out')
        {
            steps {
                script
                {
                    sh ' echo "This is git check out stage" '
                }
            }
        }
        stage('Build')
        {
            steps {
                script
                {
                    sh ' echo "This is Build stage" '
                }
            }
        }
        stage('Test')
        {
            steps {
                script
                {
                    sh ' echo "This is Test stage" '
                }
            }
        }  
        stage('Deploy')
        {
            steps {
                script
                {
                    sh ' echo "This is Deploy stage" '
                }
            }
        }                      
    }
}
