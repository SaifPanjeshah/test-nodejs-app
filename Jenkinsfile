pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing is done"'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "application deployed done"'
         }

     }
  
   	}

   }
