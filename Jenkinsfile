pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Run PMD scan') {
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
