pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
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
		#chmod 755 test2.py
		cp test2.py /var/www/cgi-bin/test2.cgi
                echo 'Deploying....'
            }
        }
    }
}


