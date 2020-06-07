pipeline {
    agent {
	label 'master'
    }
    stages {
	stage ('deploy') {
	    steps{
		sh 'rsync -r  "/var/lib/jenkins/workspace/test-new-git/" "/data/www/" --progress --stats' 
	    }
	}
}

}