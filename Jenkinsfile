pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Read Manifest Config') {
	    steps {
		echo 'Testing..'
		def configVal = readYaml file: "https://github.com/amitkapis/spring-boot-app.git/action.yml"
	
	}
}
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
