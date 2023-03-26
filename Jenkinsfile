node("master")
{
  stage("code build")
  {
    sh 'mvn clean install'
  }
  stage("unit test execution")
  {
    sh 'mvn test'
  }
  stage("junit test result")
  {
    junit '*/**/*.xml'
  }
}
  
