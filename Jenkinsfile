pipeline{
	agent any
	stages{
		stage("Cloning....."){
			steps{
				echo "repo cloned..."
			}
		}
		stage("Execution..."){
                        steps{
                                sh 'java Sample.java'
                        }
                }
	}
}
