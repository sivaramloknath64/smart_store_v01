pipeline {
	agent any
	stages {
		stage('nugget restore'){
			steps{
				  echo "nugget restoring packages"
				bat "nuget restore \"${workspace}/src/SmartStoreNET.sln\""
				
				
					}
				}
				stage('Build') {
    					steps {
              echo   " building "
    					}
				}
			}
}
