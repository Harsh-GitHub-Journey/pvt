pipeline {
        agent { node { label 'Slave-SSH' } }
                  stages {
                          stage("Env Variables") {
                                  steps {
                                          echo "The build no is ${BUILD_NUMBER}"
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


                
