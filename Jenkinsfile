def workspace;
node
 {
     stage('checkout')
     {
         checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/anilrathan/leadapp-mvn.git']]])
     }
     stage('Source code Analysis')
     {
         echo "Source code Analysis"
     }
     stage('Build')
     {
         echo "Code Build programe"
     }
     stage('Unit testing')
     {
         echo "Code Unit testing"
     }
     stage('Delivery')
     {
         echo "code Delivery"
     }
 }
 
