pipeline {
        agent any 
                  stages {
                          stage("Env Variables") {
                                  steps {
                                          echo 'You can also use \${BUILD_NUMBER} -> ${BUILD_NUMBER}'
                                  }
                          }
                          stage('hello') {
                              steps {
                                echo 'hello world'
                              }
                          }
                          stage('bye-bye') {
                              steps {
                                echo 'have a nice day'
                
                              }
                          }
                        
                  }
}


                
