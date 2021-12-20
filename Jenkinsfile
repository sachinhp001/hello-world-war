pipeline{
    agent{label'java'}
    stages {
        stage('checkout') {
            steps {	
	sh 'git clone https://github.com/akshayvdes/hello-world-war.git'	
              }
        }
	
	 	 stage('print') {
            steps {	
	sh 'echo "hello world"'	
              }
        }    
    }
}
