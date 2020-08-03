pipeline{
    agent any
    tools{
    maven 'maven-3.6.3'
    jdk 'JDK8'
    }
    stages{
        stage('Prepration'){
            steps{
                echo "Prepration stage!!"
                sh """
                echo "PATH = ${PATH}"
                echo "M2_HOME = ${M2_HOME}"
                """
            }
            
        }
        stage('Build stage'){
            steps{
                sh "pwd"
                
            }
        }
        stage('Test stage'){
            steps{
                // Test stage
                echo "Nothing!"
            }
        }//Test
    }
}
