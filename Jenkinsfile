pipeline {
    agent any
    
    stages {
        
        stage('github-clone') {
            steps {
                git branch: 'BE', credentialsId: 'github_key', url: '{REPOSITORY URL}'
            }
        }
        
   		// stage...
   	}
}
