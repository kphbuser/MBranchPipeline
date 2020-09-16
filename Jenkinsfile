pipeline {
    agent any
    stages {
        stage('Build') {
            when {
                branch 'sprint1'
            }
            steps {
                sh 'java -version'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy stage'
            }
        }
        stage('Release') {
            steps {
                echo 'Finel Releasing'
            }
        }
        stage('Sprint1') {
            steps {
                echo 'Trails Sprint1'
            }
        }
        stage('Sprint2') {
            steps {
                echo 'Sprint2 Trail'
            }
        }
        stage('sprint') {
            steps {
                echo 'sprint'
            }
        }
    }
}
