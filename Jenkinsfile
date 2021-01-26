pipeline{
	any agent
		stages{
			stage('Build'){
			steps{
				sh "echo 'My first Pipeline'"
				sh '''
					sh 'echo "Showing mutilple steps"'
					ls -ahl
				'''
			}

		}
		stage('Test'){

		}
		stage('Deploy'){

		}
}
}
