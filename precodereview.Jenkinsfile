#!/usr/bin/env groovy

pipeline {
    agent {
        node {
            label env.NODE_LABEL
        }
    }

    options {
        timestamps()
        timeout(time: 60, unit: 'MINUTES')
    }

    environment {
        KUBECONFIG = "${WORKSPACE}/.kube/config"
    }

    stages {
        stage('Prepare') {
            steps {
                echo 'Prepare Stage Placeholder'
            }
        }

        stage('Init') {
            steps {
                echo 'Init Stage Placeholder'
            }
        }

        stage('Lint') {
            steps {
                echo 'Lint Stage Placeholder'
            }
        }

        stage('Publish') {
            steps {
                echo 'Build Stage Placeholder'
            }
        }
    }
}