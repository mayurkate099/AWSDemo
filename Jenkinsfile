def buildInfo
pipeline {
     agent none
      stages {
          stage('Gradle build') {
                    buildInfo = rtGradle.run  buildFile: 'build.gradle'
          }
        
         
}
}
