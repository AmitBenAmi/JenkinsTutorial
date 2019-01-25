pipeline {
    agent { 
		docker { 
			image 'node:6.3'
			args '-w /C\Users\User\.jenkins\workspace\My_Pipeline_master -v /C\Users\User\.jenkins\workspace\My_Pipeline_master:C:\Users\User\.jenkins\workspace\My_Pipeline_master:rw,z -v /C\Users\User\.jenkins\workspace\My_Pipeline_master@tmp:C:\Users\User\.jenkins\workspace\My_Pipeline_master@tmp:rw,z'
		}
	}
    stages {
        stage('build') {
            steps {
                bat 'npm --version'
            }
        }
    }
}
