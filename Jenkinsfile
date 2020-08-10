pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		sh sudo mkdir /var/www/html/wors
		sh cp -r * /var/www/html/wors/
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
