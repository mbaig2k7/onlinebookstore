pipeline {  
    agent any  
    environment {
        PATH = "/opt/apache-maven-3.9.5"
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
                    sh 'mvn -X clean package'
                      }
            }
        }
}
