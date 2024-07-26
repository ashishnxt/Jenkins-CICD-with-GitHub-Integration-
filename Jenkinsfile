pipeline {
agent any
environment {
SONAR_PIPE = tool "sonar"
}
stages {
   stage("code") {   
        steps {    
            echo "this is awesome"
            
        }
    }
    stage("test") {
        steps {
            
                echo "this is also awesome"
                // Add more test-related steps here
         
        }
    }
    stage("build") {
        steps {
          
                echo "building..."
                // Add build-related steps here
          
        }
    }
    stage("scan") {
        steps {
           
                echo "scanning..."
                // Add scan-related steps here
            
        }
    }
    stage("deploy") {
        steps {  
          
                echo "deploying..."
                // Add deployment-related steps here
        }
     }
  }
}
