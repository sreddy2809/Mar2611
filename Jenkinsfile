pipeline{
	agent any
	stages{
		stage("One"){
			steps{
			   echo "Stage One"
			   git 'https://github.com/sreddy2809/Mar2611.git'
			  
			}
		}
		stage("Two"){
           when  { 
		       expression { branch 'master' }
		   }
           steps{
				echo "Stage two"
			}		   
		}
	}
}
