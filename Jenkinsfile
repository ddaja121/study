pipeline {
    agent { label 'slave01' }

    tools { 
        maven 'Maven3.9.6'
        jdk "JDK1.8"
    }
    
    stages {
        
        stage('github-clone') {
            steps {
                git branch: 'main', credentialsId: 'github_key', url: 'https://github.com/ddaja121/study.git'
            }
        }

        stage('Build') {
            steps {
                sh "mvn clean package"
            }
        }

            
   		// stage...
   	}
}
