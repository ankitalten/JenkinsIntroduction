pipeline
{
	agent any
	stages
	{
		stage('Preparing')
		{
			steps 
			{
				echo "I'm in stage Preparing!"
				deleteDir()
				checkout scm
				echo "Finished getting files from github repository"
			}
		}
		stage('Build')
		{
			steps
			{
				echo 'I am in Build stage'
				echo 'Finished building'
			}
		}
		stage('Testing')
		{
			steps
			{
				echo 'I am in the testing stage'
				echo 'Finished testing'
			}
		}
		stage('Deploying')
		{
			steps
			{
				echo 'I am in the deploying stage'
				echo 'Finished deploying'
			}
		}
	}
}
