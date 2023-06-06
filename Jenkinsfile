pipeline{
  agent{
         label "Master"
	}
  stages{
	  stage('checkout')
	   {
	     steps{
		    git credentialsId: '15f0a019-ecce-4205-bf7b-0ddaccba1fa3', url: 'https://github.com/stpl-pro/jenkins-calculator.git'
     		  }
	   }
  stages{
          stage('checkout')
           {
             steps{
                    sh "mvn clean package"
                  }
           }

        }
}
 
