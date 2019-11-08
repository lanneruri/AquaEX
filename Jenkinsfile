node('slave1'){
   checkout scm
   sh "apt upadte"
   sh "apt install docker"
   sh "docker build -t ubuntu-test ."
}
