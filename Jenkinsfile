pipeline { 
    agent any  
    stages { 
        stage('Build') { 
            steps { 
               sh mvn clean Tomcat Web App 
            }
        }
    }
}
