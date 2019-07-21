def buildInfo
pipeline {
     agent any
     stages {
          stage('Gradle build') {
                    buildInfo = rtGradle.run  buildFile: 'build.gradle'
           
          }
         
}
}
