node(){
   stage('git pull'){
     dir('/home/agira/jenkins-test/multibranch'){
      sh 'git config --global --add safe.directory /home/agira/jenkins-test/multibranch/multibranch'
                sh 'git stash'
        sh 'git reset --hard'
     sh ' git pull origin production --allow-unrelated-histories'
     }
   }
}
