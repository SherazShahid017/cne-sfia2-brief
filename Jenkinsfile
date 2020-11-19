pipeline{
    agent any
	stages{
            ////////////////////////////////////////////////////
            stage ('Build') {
                steps {
                    sh 'sudo docker build -t sherazshahid017/project-app:latest ./backend/'
		    sh 'sudo docker push sherazshahid017/project-app:latest'
                }
            }
	}
}
