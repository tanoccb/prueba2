pipeline {
	agent any
	stages {
		stage('Build'){
			steps{
				sh "docker build -t tanoccb/pokedex-flask:${env.BUILD_NUMBER} ."
			}
		} 
	}
}
