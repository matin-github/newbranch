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
	stage('Continuous Deplyoment') {

    sh 'scp  /home/ubuntu/workspace/workspace/scrpitedpipeline/webapp/target/webapp.war   ubuntu@172.31.20.217:/var/lib/tomcat9/webapps/qaenv.war'

	}
}
