pipeline {
	agent any
	stages {
		stage('build') {
			steps {
				sh '''
				git clone https://github.com/Darshan629/java-project.git
				cd /var/lib/jenkins/workspace/pipelinejob1/java-project/
				mvn clean 
				mvn install
				'''
			
			}
		}
	}
}
