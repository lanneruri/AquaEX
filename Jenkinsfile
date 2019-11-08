node('slave1'){
   checkout scm
   sh "apt-get upadte"
   sh "apt-get install docker"
   sh "docker build -t ubuntu-test ."
}
