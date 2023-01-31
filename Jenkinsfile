
@Library("roboshop") _

pipeline{
  agent any
  stages{
    stage('test')
    {
    steps{
    script
    {
      def abc = "hello"
      env.am = "hi"
      def a = 10

      print  "abc = ${abc}"

      print abc

    }
    }
    }
    
  stage('test2')
  {
  steps{
  script
  {
  print "abc= $(abc)"
  
  }
  }
 
  }
  
  
  }

}