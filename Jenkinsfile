pipeline {
    agent any
    stages {
        stage('code pull') {
            steps {
                git branch: "main", url: 'https://github.com/neelufars/repo-99.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn install'
            }
        }
    }
}
