node('built-in') 
{
    stage('Continuous Download_chnd') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_chnd') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
