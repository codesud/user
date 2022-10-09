@Library('roboshop-shared-library@main')
pipeline {
    agent any
    stages {
        // This should run for every commit of feature branch
        stage('Lint checks') {
            steps {
                script {
                    nodejs.lintcheck()
                }
            }
        }
    } //end of the stages
}  // end of the pipeline