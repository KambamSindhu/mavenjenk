pipeline{
    agent any

   stages
  {
        stage('checking out code ')
      {
          steps
          {
           sh  'checkout scm'
          }
       }
   
      stage('Running Test')
      {
          steps
          {
           sh  'mvn -f mavenjenk/pom.xml clean test'
          }
       }
   
}
}
