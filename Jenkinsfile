pipeline {
    agent any
    parameters{
        string(name: 'NAME', defaultValue: 'world', description: 'Person Name')
    }
    stages {
        stage('Hello') {
            steps {
                echo "Hello ${params.NAME}"
            }
        }
    }
    stages {
        stage('List all files') {
            steps {
                ls- a
            }
        }
    }
}