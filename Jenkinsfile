pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage("Read Manifest Config") {
	node {
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
