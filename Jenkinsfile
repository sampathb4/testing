node('built-in') {
    // some block
	stage('Continous Download') 
	{
    // some block
	git 'https://github.com/sunildevops77/maven.git'
	}
	stage('Continous Build') 
	{
    // some block
	sh 'mvn package'
	}
	stage('Continous Deployment') 
	{
    // some block
	sh 'scp /home/ubuntu/.jenkins/workspace/PipelineJob/webapp/target/webapp.war	ubuntu@172.31.39.126:/var/lib/tomcat8/webapps/qaenv1.war'
	}
	stage('Continous Testing') 
	{

}
