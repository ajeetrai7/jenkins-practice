pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                 sh  set-ex
		 echo 'Building..'
            }
        }
         stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
     }
}
