node('master') 
{
    stage('Continuous Download_loan') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_loan') 
	{
    sh label: '', script: 'mvn package'
	}

}
