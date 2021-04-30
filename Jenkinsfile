node{
  stage('scm checkout'){
    git branch: 'main', url: 'https://github.com/nitheshkumar229/rapido-web-app.git'
  }
  stage('build'){
  def mvnhome= tool name: 'maven3', type: 'maven'
    sh '${mvnhome}/bin/mvn package'

  }
}
