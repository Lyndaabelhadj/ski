pipeline {
agent any
  stages {
   stage ('Git') {
        steps {
          echo 'Git ...'
        }
      }
  stage ('MVN Compile') {
        steps {
          echo 'Compilee ...'
        
        }
      }
  stage ('MVN Build') {
        steps {
          echo 'Building ...'
       
        }
      }
  stage ('MVN Test') {
        steps {
          echo 'Testing ...'
        
        }
      }
  stage ('Sonar') {
        steps {
          echo 'Sonaaar ...'
         
        }
      }
  stage ('Deploy') {
        steps {
          echo 'Cleaning ...'
      
        }
      }
  stage ('Nexus') {
        steps {
          echo 'Nexus ...'
      
        }
      }
  }
}
