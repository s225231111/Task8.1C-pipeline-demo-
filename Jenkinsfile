pipeline {
agent any
stages {
stage('Build') {
    steps {
        echo "Build pipeline using Maven"
    }
}
    stage('Unit and Integration Tests ') {
        steps {
            echo "Testing using Selenium"
        }
}
    stage('Code Analysis') {
        steps {
            echo "Analysis codes using SonarQube"
        }
}
    stage('Security Scan') {
        steps {
            echo "Security Scan using OWASP Dependency-Check "
        }
}
    stage('Deploy to Staging') {
        steps {
            echo "Deploy using AWS CLI"
           
    }
}
stage('Integration Tests on Staging ') {
        steps {
            echo "Test using Selenium:"
    }

stage('Deploy to Production ') {
    steps {
        echo "Deploying the code using AWS CLI:"
    }
}
}
}
}