pipeline {
        agent any 
                  stages {
                          stage('hello') {
                              steps {
                                echo 'hello world'
                              }
                          }
                          stage('bye-bye') {
                              steps {
                                echo 'have a nice day'
                                      sh '''touch 1.txt'''
                              }
                          }
                        
                  }
}


                
