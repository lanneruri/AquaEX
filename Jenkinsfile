node('slave1'){
   checkout scm
   sh "docker build -t ubuntu-test ."
   sh "docker images"
}
