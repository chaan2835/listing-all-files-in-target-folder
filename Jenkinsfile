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
      
		// sh "ls -R ${WORKSPACE}"
		//sh "cd target"
		//sh "ls -l"
		dir("${env.WORKSPACE}/aQA"){
    sh "pwd"
}
        }
    }
	}
}
			
