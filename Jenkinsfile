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
                                bat 'java Sample.java'
                        }
                }
	}
}
