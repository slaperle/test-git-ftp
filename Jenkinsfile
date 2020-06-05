pipeline {
    agent {
	label 'master'
    }
    stages {
	stage ('deploy') {
	    steps{
		sh 'sshpass -p Pr0metheu$ rsync -r  /var/lib/jenkins/workspace/test-new-git/ root@10.54.121.141:/data/www/ --progress --stats' 
	    }
	}
}

}