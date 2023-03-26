pipeline{
    agent any

   stages
  {
        
   
      stage('Running Test')
      {
          steps
          {
           sh  'mvn -f mavenjenk/pom.xml clean  install test'
          }
       }
      
     stage('Junit test result')
      {
          steps
          {
              junit '*/**/*.xml'
          }
      }
   
}
}
