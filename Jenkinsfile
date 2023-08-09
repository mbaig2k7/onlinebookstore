pipeline {  
    agent any  
    environment {
        PATH = "/opt/apache-maven-3.9.2"
        }
        stages {  
       	    stage("git_checkout") 
             {  
           	    steps {  
              	    echo "cloning repository" 
              	    echo "repo cloned successfully"  
              	      }  
         	 } 
            stage("mvn build") 
            {
                steps {
                    sh 'mvn clean package'
                      }
            }
        }
}
