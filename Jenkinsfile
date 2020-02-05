pipeline {
    
    stages {
        stage('---checkout---') {
            steps {
                git "https://github.com/dkshahi/my-app.git"
            }
        }
        stage('---clean---') {
            steps {
                sh "mvn clean"
            }
        }
        stage('--test--') {
            steps {
                sh "mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "mvn package"
            }
        }
    }
}