  
@Library('shared-ssmd-library') _

pipeline{
        agent any
        stages{

              stage('Quality Gate Status Check'){
                  steps{
                      config {
				  sh "${commanJenkinsTemplate()}"
			  }

               	 }  
              }	
		
            }	       	     	         
}
