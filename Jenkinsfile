pipeline{
    agent{label'java'}
  stages{
    stage('checkout'){
       steps{
          sh'git clone https://github.com/sachinhp001/hello-world-war.git'
	}
      }

	  stage('build'){
	steps{
          sh'mvn clean pakage'
	}
     }
	 stage('print'){
	step{
	  sh'echo "hello world"'
         }
      }
   }
}
