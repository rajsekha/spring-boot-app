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
		    //def configVal = readYaml file: "action.yml"
		    def jobParameters = new Yaml().load(new FileReader('https://github.com/amitkapis/spring-boot-app.git/action.yml'))
		
	}
}
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
