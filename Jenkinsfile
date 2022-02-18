node('built-in') 
{
    stage('Continuous Download_nagu') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_nagu') 
	{
    sh label: '', script: 'mvn package'
	}
}
