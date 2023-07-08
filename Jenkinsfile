pipeline {
  agent any 
   stages {
     stage('Pull'){
       steps{
           script{
             checkout([$class:'GitSCM',branches:[[name: '*/main']],
              userRemoteConfigs:[[
                url:'https://github.com/MarouaMad/angular-8-7.git']]])
           
           }

}
}
}

}
