node('slave1'){
   checkout scm
   sh "yum install docker"
   sh "docker build -t ubuntu-test ."
}
