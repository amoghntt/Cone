pipeline {
    agent any
  
    stages {
        stage ('Initialize') {
            steps {
               
                    echo "PATH = ${PATH}"
                    echo "MAVEN_HOME = ${MAVEN_HOME}"
     
            }
        }

        stage ('Build') {
            steps {
              bat "mvn  clean install"
            }
       
        }
    }
}
