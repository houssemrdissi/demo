pipeline {
        agent any
        
        tools{
                maven 'Maven'
        }
        stages{
            stage('build'){
                steps {
                 echo "buiiiiiiiiiiiiiii"
                        sh "mvn clean -f demo"

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
