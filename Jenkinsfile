pipeline {
    agent any
    tools { 
        maven 'M2_HOME' 
        jdk 'JAVA_HOME' 
    }
    stages {
        stage ('Initialize') {
            steps {
               
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
     
            }
        }

        stage ('Build') {
            steps {
              bat "mvn  test"
            }
       
        }
    }
}
