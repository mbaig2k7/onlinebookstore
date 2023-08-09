pipeline {  
    agent any  
        stages {  
       	    stage("git_checkout") {  
           	    steps {  
              	    echo "cloning repository" 
              	    echo "repo cloned successfully"  
              	    }  
         	    } 
            stage("mvn build") {
            steps {
                    sh 'mvn -X clean package'
                }
        }
        }
}
