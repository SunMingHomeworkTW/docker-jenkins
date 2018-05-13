#!/usr/bin/env groovy Jenkinsfile
node{
    def gradleHome = tool 'Gradle 4.7'
    env.PATH = "${gradleHome}/bin:${env.PATH}"
}
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'gradlew bootRun'
            }
        }
        stage('Test') {
            steps {
                sh 'gradlew test'
            }
        }

    }
}