pipeline {
	agent: any
	
	environment {
		DOCKER_IMAGE = 'dasolson/boot-app'	
	}
	
	stages {
		stage('Git -> Jenkins 연결 확인') {
			steps {
				echo 'GitHub push 감지 성공'
			}
		}
	}
}	 