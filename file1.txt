pipeline {
    agent any
        stages('Compile Stage') {
        
            steps {
                sh 'mvn --version'
                  }
                                }
    
        }
