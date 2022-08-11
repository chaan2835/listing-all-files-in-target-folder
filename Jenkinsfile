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
      
		// sh "ls -R ${WORKSPACE}"
	
		sh "ls -l"
		// dir("${env.WORKSPACE}"){
   		// sh "pwd"
		//	}
		//sh "cd target"
		//sh "pwd"
       		}
    }
	}
}
}		
