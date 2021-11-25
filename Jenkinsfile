pipeline {
  agent any
  triggers {
    pollSCM('* * * * *')
  }
  stages {
    stage('stage1') {
      steps {
        sh 'echo "hello,  stage1 from nari"'
      }
    }

    stage('stage2') {
      steps {
        sh 'echo "hello, mounika"'
        git(url: 'https://github.com/mounika998/mounikak.git', branch: 'main', poll: true)
      }
    
        
         
   
          }

  }
}
