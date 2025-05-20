pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Run Python') {
            steps {
                sh 'python3 oop_solutions.py'
            }
        }
    }
}
