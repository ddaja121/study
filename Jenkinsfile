pipeline {
    agent { label 'slave01' }
    
    stages {
        
        stage('github-clone') {
            steps {
                git branch: 'main', credentialsId: 'github_key', url: 'https://github.com/ddaja121/study.git'
            }
        }
        
   		// stage...
   	}
}
