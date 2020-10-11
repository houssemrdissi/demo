pipeline {
        agent any
        
        tools{
                maven 'Maven'
        }
        stages{
            stage('clean'){
                steps {
                 echo "clean project"
                 bat "mvn clean"

                }
            }
            stage('Test'){
                steps{ 
                 echo "test project"
                 bat "mvn test"
                        
                }
            }
            stage('Deploy'){
                steps {
                 echo "Deploy project"
                 bat "mvn package"
                 bat "mvn deploy"
bat "mvn sonar:sonar"
                        
                }
            }
        }
}
