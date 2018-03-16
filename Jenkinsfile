pipeline {
   agent any
   
   stages {

      stage('foo') {
         steps {
            print 'foo'
         }
      }      
      stage('sleep') {
         steps {
            sleep 10
         }
      }
      stage('bar') {
         steps {
            print 'bar'
         }
      }         
   }
}
