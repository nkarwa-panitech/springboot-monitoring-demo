pipeline {
    agent {label 'node01'}
    tools { 
        maven '3.9.0' 
    }
    stages {
        stage ('Build') {
            steps {
                sh 'mvn package' 
            }
        }
    }
}
