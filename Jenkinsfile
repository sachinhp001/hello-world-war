pipeline{
    agent{label'java'}
  stages{
    stage('checkout'){
       steps{
          sh'git pull https://github.com/sachinhp001/hello-world-war.git'
	}
      }

	  stage('build'){
	steps{
          sh'mvn clean package'
	}
     }
	 stage('print'){
	step{
	  sh'echo "hello world"'
         }
      }
   }
}
