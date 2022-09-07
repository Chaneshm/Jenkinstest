pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
      sh 'echo "HELLO chanesh"'
      sh '''
        echo "Thi will list current dir content from latest"
        ls -lh
        '''
      }
    }
    stage ('Test') {
      steps {
      sh 'echo "HELLO branch2"'
      sh '''
        echo "This list current dir"
        pwd
        '''
      }
    }
  }
}
