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
		pmd -d src/main -R ruleset.xml >>Pmdlog.txt
		'''
	    }
        }
    }
}
