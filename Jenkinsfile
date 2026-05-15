pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Stage 1: Build - Compiling and packaging the code using Maven.'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Stage 2: Unit and Integration Tests - Running tests using Selenium.'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Stage 3: Code Analysis - Analysing code quality using SonarQube.'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Stage 4: Security Scan - Scanning vulnerabilities using OWASP Dependency-Check.'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Stage 5: Deploy to Staging - Deploying application to AWS EC2 staging server.'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Stage 6: Integration Tests on Staging - Testing deployed app using Postman/Newman.'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Stage 7: Deploy to Production - Deploying final application to AWS EC2 production server.'
            }
        }
    }
}
