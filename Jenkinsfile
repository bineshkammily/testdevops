pipeline {

	agent any 

	stages {

			stage('Build'){
				steps {
					echo "Testing Build.............!!"

				}

			}

			stage ('Test'){

				steps {
					echo "Testing Stage..............!!!"	

				}

			}

			stage ('Run My Script'){

				steps {
					sh("rere.sh")
				}

			}

			stage ('Deploy'){

				steps {
					echo "Testing Deployment Stage..............!!!"	

				}

			}
	}

}		
