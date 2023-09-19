node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/abrarathani/1231.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    }
