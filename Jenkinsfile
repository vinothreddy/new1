node('loans') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/vinothreddy/new1.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	
}
}
