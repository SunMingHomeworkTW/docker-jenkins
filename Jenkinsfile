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
                echo 'Building....'
            }
        }
        stage('Test') {
            steps {
                echo 'Building....'
            }
        }

    }
}