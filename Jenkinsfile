pipeline{ 
        agent any 
        stages{ 
                stage('Make Directory'){
                     steps{ 
                        sh "mkdir ~/jenkins-tutorial-test1" 
                    } 
                } 
                stage('Make Files'){ 
                    steps{ 
                        sh "touch ~/jenkins-tutorial-test1/file1 ~/jenkins-tutorial-test1/file2" 
                    } 
                } 
        } 
}
