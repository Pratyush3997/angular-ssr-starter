nodejs('NodeJS'){
  stage('Checkout SCM'){
 git credentialsId: 'javahome2', url: 'https://github.com/KoilakuntlaRasool/angular-ssr-starter.git'
  }
  stage('build code'){
    sh "npm install"
  }
  stage('build code'){
    sshagent(['a36cca7a-fac2-463d-a84e-0071b39725fc']) {
    sh 'src/index.html ec2-user@18.220.253.133'
      }
  }
}
