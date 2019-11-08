node('slave1'){
   checkout scm
   sh "sudo apt-get update"
   sh "sudo apt-get install docker"
   sh "docker build -t ubuntu-test ."
}
