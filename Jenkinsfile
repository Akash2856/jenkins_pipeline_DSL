pipeline

agent any

stages{

	stage SCM('SCM'){
			Steps {
				echo "git pull my code"
		      		}  
	}
 
	stage deploye('Deploy'){
			Steps{ 
		     	echo "deploying the code"
		     	}
	}

	stage Test('Test'){
			Steps{ 
		     	echo "test my final webapp"
		     	}
	}

}
