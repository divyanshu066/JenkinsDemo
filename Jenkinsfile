#
pipeline {
    agent any
        stages {
           stage('Build') {
            steps {
                echo 'Building..'
                  }
                          }
            stage('Test') {
                steps {
                echo 'Testing'
                    
                      }
                          }   
            stage('Junit'){
                steps {
                    
                    echo 'Junit'
                         }
                      }
            stage('Deploy'){
                steps {
                    echo 'Deploy'
                }
            
            }
        
        }
    
    post {   
always {  

archiveArtifacts artifacts: '*.jar' ,fingerprint: true
       }
         }
}
