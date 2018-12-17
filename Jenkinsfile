node {  
   lock('DockerContainer') {
  properties([disableConcurrentBuilds()])
   stage('checkout and clean') {
     deleteDir()	
     checkout scm
   }
   stage('Build') {
       sh 'ls -al ; git branch; df -h; sleep 45'
       sh 'echo "This is testing of new JenkinsFile under hellowordapp"'
       sh 'ls -la; cat Jenkinsfile; git branch; git log; sleep 60'
       }
   }
}
