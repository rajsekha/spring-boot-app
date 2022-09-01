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
		    bat '''
		    readYaml file: "action.yml"
		    '''	
	    }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
