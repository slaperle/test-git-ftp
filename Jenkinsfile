pipeline {
    agent {
	label 'master'
    }
    stages {
	stage ('deploy') {
	    steps{
		sh 'rsync -r "$WORKSPACE/test-git/" root@10.54.121.141:/data/www/'
	    }
	}
}

}