node('slave1'){
   checkout scm
   sh "apt update"
   sh "apt install docker"
   sh "docker build -t ubuntu-test ."
}
