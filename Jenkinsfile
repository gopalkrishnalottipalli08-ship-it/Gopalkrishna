    // Example Jenkinsfile (scripted pipeline)
    node {
        stage('Checkout') {
            checkout scm
        }
        stage('Build') {
            sh 'mvn clean install' // Example build command
        }
        stage('Test') {
            sh 'mvn test' // Example test command
        }
        stage('Deploy') {
            // Add deployment steps here
            echo 'Deployment complete!'
        }
    }
