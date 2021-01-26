node{
		stage('Build'){
			steps{
				sh "echo 'My first Pipeline'"
				sh '''
					sh 'echo "Showing mutilple steps"'
					ls -ahl
				'''
				retry(3) {
					sh "this job would fail"
					}
			}

		}
		stage('Test'){

		}
		stage('Deploy'){

		}
}
