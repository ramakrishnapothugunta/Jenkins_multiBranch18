node('built-in') 
{
    stage('ContinuousDownload_rk') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuousbuild_rk') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
