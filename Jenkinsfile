pipeline{
    agent any
            ////////////////////////////////////////////////////
            stage ('Build') {
                steps {
                    sh 'sudo docker build -t sherazshahid017/project-app:latest'
		    sh 'sudo docker push sherazshahid017/project-app:latest'
                }
            }
}
