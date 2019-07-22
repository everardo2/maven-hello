pipeline {
    agent any
    stages{
        stage('Build'){
            steps {
                sh 'mvn clean -f Tomcat-Web-App'
            }
         }
    }
}
