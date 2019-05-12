pipeline{
      agent any
	  stages{
	        stage('one'){
		           steps{ echo 'saddique pipeline' }
				   }
			stage('two'){
			       steps{ echo'this is step two' }
				   }
            stage('three'){
			        steps{ echo'this is step two' }
					}	
            stage('four'){
			     parallel{
				    stage('Unit testing'){
					      steps{ echo 'unit test is in progress'}
						  }
				    stage('deployment'){
					      steps{ echo 'deployment is in progress'}
						  }
					 
					}
			    } 					
     		}
						 
		}