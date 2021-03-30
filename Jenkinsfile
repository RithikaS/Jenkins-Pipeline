pipeline {
    agent any
    tools{nodejs "node"}
    stages {
        stage('Hello') {
            steps {
                echo 'helloooooo'
            }
        }
        stage('run script') {
            steps {
                bat 'node greet.js'
            }
        }
    }
}
