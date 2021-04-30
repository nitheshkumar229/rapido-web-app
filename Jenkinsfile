node{
  stage('scm checkout'){
    git branch: 'main', url: 'https://github.com/nitheshkumar229/rapido-web-app.git'
  }
  stage('build'){
  def mvnHome= tool name: 'maven3', type: 'maven'
    sh 'echo $mvnHome'
   sh '''${mvnHome}/bin/mvn package'''

  }
}
