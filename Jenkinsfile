pipeline {
    agent { label 'slave01' }
    
    stages {
        
        stage('github-clone') {
            steps {
                git branch: 'main', credentialsId: 'github_key', url: 'https://github.com/ddaja121/study.git'
            }
        }

        stage('Build') {
            steps {
                sh "export PATH=$PATH:$HOME/bin:/var/jenkins_home/apache-maven-3.9.6/bin; mvn clean package"
            }
        }

            
   		// stage...
   	}
}
