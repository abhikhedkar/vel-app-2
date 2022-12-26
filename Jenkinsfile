pipeline {

         agent {
		 
		         label {
				         label 'built-in'
						 customWorkspace '/mnt/myproject'
				 }
		 
		 }
		 
		 stages {
		 
		          stage ('stage-1') {
				  
                     				                 steps {
								         sh "mkdir test3"
								 }
				  }
				  
				  
				    stage ('stage-2') {
				  
				                 steps {
										         sh "mkdir folder3"
								 }
				  }
		 }
}
