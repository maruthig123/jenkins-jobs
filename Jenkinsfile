node {
stage('Git Checkout')
  {
'https://github.com/maruthig123/jenkins-jobs'
  }
stage('Compile and package')
{
  def mvnHome = tool name: 'maven3', type: 'maven'
  sh "${mvnHome}/bin/mvn package"
}
}

