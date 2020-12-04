  
@Library('shared-ssmd-library') _

pipeline{
        
        stages{

              stage('Quality Gate Status Check'){
                  steps{
                      config {
				  sh "${mavenBuild()}"
			  }

               	 }  
              }	
		
            }	       	     	         
}
