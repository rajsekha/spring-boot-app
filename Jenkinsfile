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
		def configVal = readYaml file: "action.yml"
	
	}
}
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
