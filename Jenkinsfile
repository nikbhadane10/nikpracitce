node {
   stage ('Checkout code') {
    checkout([$class: 'GitSCM', branches: [[name: '**']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '12345', url: 'https://github.com/nikbhadane/hellowordapp']]])
  }
stage ('Final') {
   echo 'Hello World'
   sh 'ls -al'
   sh 'cat *'
   sh 'df -h'
  }
}
