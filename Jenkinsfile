pipeline {
    agent any

    stages {
        stage('Processo de Build') {
            steps {
                echo 'Building a aplicação...'
                sh 'mvn clean package'
                // Add your build steps here
            }
        }      
}