pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git credentialsId: 'your-github-credentials-id', url: 'https://github.com/your-username/your-repo.git'
            }
        }
        
        stage('Deploy to XAMPP') {
            steps {
                sh 'cp *.html /path/to/xampp/htdocs/'
            }
        }
    }
}

