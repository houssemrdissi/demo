pipeline {
        agent any
        
        tools{
                maven 'Maven'
        }
        stages{
            stage('build'){
                steps {
                 echo "buiiiiiiiiiiiiiii"
                        sh "mvn install"

                }
            }
            stage('Test'){
                steps{ 
                   echo "tes"
                        
                }
            }
            stage('Deploy'){
                steps {
                 echo "dep" 
                }
            }
        }
}
