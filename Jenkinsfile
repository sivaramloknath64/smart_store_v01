pipeline {
	agent any
	stages {
		stage('nugget restore'){
			steps{
				  echo "nugget restoring packages"
			bat 'C:/tools/nuget.exe  restore SmartStoreNet.sln'
				
				
				
					}
				}
				stage('Build') {
    					steps {
              echo   " building "
    					}
				}
			}
}
