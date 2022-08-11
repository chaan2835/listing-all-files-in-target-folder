pipeline { 
	agent any
		stages {
	
			stage ('build'){
					
							steps {
							
							sh 'mvn install'
					       			}
						}
	stage('listing-files-in-workspace') {
        steps {
		script {
		def pwd="${WORKSPACE}/target"
		sh "ls -R $pwd"
		// sh "ls -R ${WORKSPACE}" (to list all files in workspace)	
      		      		}
    			}
		}
	}
}		
