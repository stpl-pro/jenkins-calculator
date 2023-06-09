pipeline{
  agent any
  {
    tool name: 'maven', type: 'maven'
  }
  stages{
	  stage('checkout')
	   {
	     steps{
		    git credentialsId: '15f0a019-ecce-4205-bf7b-0ddaccba1fa3', url: 'https://github.com/stpl-pro/jenkins-calculator.git'
     		  }
           }
          stage('Build')
           {
             steps{
                    sh "mvn clean package"
                  }

	   }

        }
}
 
