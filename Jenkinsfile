node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
	stage('Continuous build')
        {
        sh 'mvn package'
	}

}

