pipeline {
    agent any 
    stages {
        stage('Lint Checks') {
            steps {
                sh "echo installing jslint"
                sh "npm i jslint"
                sh "node_modules/jslint/bin/jslint.js server.js"
            }
        }
    }
}