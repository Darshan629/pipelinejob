pipeline {
	agent any
	stages {
		stage ('build') {
			steps {

					sh '''
		echo "this is build stage"
		'''
		stage ('test') {
				steps {
			sh '''
			echo "this is test stage"
				'''
					stage ('my stage') {
						steps {
							sh '''
								echo "this is my stage"
									'''
						}
					}


			}

		}
				}
			}
	
		}
	
	}
}
