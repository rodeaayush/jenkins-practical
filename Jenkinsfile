pipeline {
    agent { label 'label1'
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'touch ayush {1..10}' 
            }
        }
    }
}
