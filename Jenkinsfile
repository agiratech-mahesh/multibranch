node(){
   stage('git pull'){
     dir('/home/agira/jenkins-test/multibranch'){
        withCredentials([gitUsernamePassword(credentialsId: 'git-sahins', gitToolName: 'Default')]) {
      sh 'git config --global --add safe.directory /home/agira/jenkins-test/multibranch'
     sh ' git pull origin testing'
     }
     }
     }
}
