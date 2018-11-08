pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('pre') {
            steps {
                sh 'mvn --help'
            }
        }
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
