pipeline { 
	agent any
		stages {
	
			stage ('build'){
					
							steps {
							
							sh 'mvn install'
					       			}
						}
					stage('sh how to') {
        steps {
      
		sh "ls -R ${WORKSPACE}"
		sh "cd target"
		sh "ls -l"
        }
    }
	}
}
			
