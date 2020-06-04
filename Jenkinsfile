pipeline {
    agent {
	label 'master'
    }
    stages {
	stage ('deploy') {
	    steps{
		sh 'rsync -r /var/lib/jenkins/workspace/test-new-git/ root@10.54.121.141:/tmp/ --progress --stats' 
	    }
	}
}

}