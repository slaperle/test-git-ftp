pipeline {
    agent {
	label 'WebServer'
    }
    stages {
	stage ('deploy') {
	    steps{
		sh 'rsync -a  /var/lib/jenkins/workspace/test-new-git/ root@10.54.121.141:/data/www/ --progress --stats' 
	    }
	}
}

}