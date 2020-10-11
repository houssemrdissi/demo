pipeline {
        agent any
        
        tools{
                maven 'Maven'
        }
        stages{
            stage('build'){
                steps {
                 echo "buiiiiiiiiiiiiiii"
                        bat "mvn clean"

                }
            }
            stage('Test'){
                steps{ 
                   echo "tes"
                        sh "mvn install"
                }
            }
            stage('Deploy'){
                steps {
                 echo "dep" 
                }
            }
        }
}
