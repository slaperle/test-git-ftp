pipeline {
    agent {
	label 'mr-mime'
    }
    stages {
	stage ('deploy') {
	    steps{
		sh 'rsync -r "$WORKSPACE/test-git/" root@10.54.121.141:/data/www/'
	    }
	}
}

}