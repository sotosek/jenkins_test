pipeline {
	agent any
	stages {
		stage('Stage1') {
			steps {
				echo 'Hello World step1'
				sh 'pwd'
				# rename and move frontend
				sh '/home/emigma/move_frontend.sh'
			}
		}
		stage('Stage2') {
			steps {
				echo 'Hello World step2'
			}
		}
	}
}