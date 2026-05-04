pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build: Compile and package code using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Testing: Run unit and integration tests using JUnit and Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Code Analysis: Analyse code quality using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Security Scan: Scan vulnerabilities using OWASP Dependency Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to staging server using AWS EC2'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running integration tests in staging environment using Postman/Newman'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying to production server using AWS EC2'
            }
        }
    }
}
