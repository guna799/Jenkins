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
                    echo "This is git check out stage"
                }
            }
        }
        stage('Build')
        {
            steps {
                script
                {
                    echo "This is Build stage"
                }
            }
        }
        stage('Test')
        {
            steps {
                script
                {
                    echo "This is Test stage"
                }
            }
        }  
        stage('Deploy')
        {
            steps {
                script
                {
                    echo "This is Deploy stage"
                }
            }
        }                      
    }
}
