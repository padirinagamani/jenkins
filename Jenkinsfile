pipeline {
  agent any
   stages {
     stage("cloning") {
         steps {
             echo "cloning repo is completed"
            }
      }
      stage("program execution") {
         steps {
             bat 'java Sample.java'
           }
      }
  }
}
