node("java") {
    stages {
        stage('checkout') {
            steps {	
	sh 'git pull https://github.com/akshayvdes/hello-world-war.git'	
              }
        }
	
	 stage('build') {
            steps {	
	sh 'mvn clean package'	
              }
        }
	 stage('print') {
            steps {	
	sh 'echo "hello world"'	
              }
        }    
    }
}
