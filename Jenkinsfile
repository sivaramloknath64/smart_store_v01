pipeline {
	agent any
	stages {
		stage('nugget restore'){
			steps{
				  echo "nugget restoring packages"
				
				bat "\"${tool 'MSBuild'}\" SmartStoreNet.sln /p:DeployOnBuild=true /p:DeployDefaultTarget=WebPublish /p:WebPublishMethod=FileSystem /p:SkipInvalidConfigurations=true /t:build /p:Configuration=Release /p:Platform=\"Any CPU\" /p:DeleteExistingFiles=True /p:publishUrl=c:\\inetpub\\wwwroot"
				
				
					}
				}
				stage('Build') {
    					steps {
              echo   " building "
    					}
				}
			}
}
