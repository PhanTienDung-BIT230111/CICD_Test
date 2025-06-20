pipeline {
 agent any
 
 stages {
	stage('clone'){
		steps {
			echo 'Cloning source code'
			git branch:'main', url: 'https://github.com/PhanTienDung-BIT230111/CICD_Test.git'
		}
	} // end clone

  } // end stages
}//end pipeline
