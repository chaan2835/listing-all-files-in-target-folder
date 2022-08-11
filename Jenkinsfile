pipeline { 
	agent {label "slave1"}
		stages {
	
			stage ('build'){
					
							steps {
							
							sh 'mvn install'
					       			}
						}
					stage('sh how to') {
        steps {
            sh 'ls -l'
	sh 'cd target '
		sh "ls -R ${WORKSPACE}"
        }
    }
	}
}
			
