pipeline {
    agent any
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    mvn clean package
                ''' 
            }
        }

        stage ('Build') {
            steps {
               sh 'mvn clean -f Tomcat-Web-App'
            }
        }
    }
}
