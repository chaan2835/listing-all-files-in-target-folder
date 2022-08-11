pipeline { 
	agent {
	label "slave1"
	}
		stages {
			stage('sh how to') {
        steps {
            sh 'ls -l'
        }
    }
			stage ('build'){
					
							steps {
							
							sh 'mvn install'
					       			}
						}
	}
}
			
