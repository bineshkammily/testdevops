pipeline {

	agent {prod_slave_lable} 

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
					sh("python hello.py")
				}

			}

			stage ('Deploy'){

				steps {
					echo "Testing Deployment Stage..............!!!"	

				}

			}
	}

}		
