pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Build using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Testing using JUnit and Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Code analysis using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Security scan using OWASP ZAP'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploy to AWS EC2 staging'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Run tests on staging'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploy to production'
            }
        }
    }
}
