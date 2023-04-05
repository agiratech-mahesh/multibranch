node(){
   stage('git pull'){
     dir('/home/agira/jenkins-test/multibranch/multibranch'){
      sh 'git config --global --add safe.directory /home/agira/jenkins-test/multibranch/multibranch'
//            git config --global user.email "mahesh.m@agiratech.com"
//   git config --global user.name "agiratech-mahesh"
  sh'  git pull origin testing --allow-unrelated-histories' 
     }
     }
}
