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
		    yamlFile "action.yml"
		
	}
}
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
