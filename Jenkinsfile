pipeline {
   agent any
   
   stages {

      stage('foo') {
         steps {
            print 'foo'
         }
      }      
      lock('myResource') {
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
}
