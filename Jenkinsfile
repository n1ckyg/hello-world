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
}