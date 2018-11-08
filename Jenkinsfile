pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stage('pre') {
            steps {
                sh 'mvn --help'
            }
        }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
