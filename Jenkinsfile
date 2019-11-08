node('slave1'){
   checkout scm
   sh "apt-get update"
   sh "apt-get install docker"
   sh "docker build -t ubuntu-test ."
}
