node {
  stage('Checkout SCM'){
 git branch: 'master', url: 'https://github.com/KoilakuntlaRasool/angular-ssr-starter.git'
  }
  stage('Install node modules'){
    sh "npm install"
  }
  stage('Build'){
    sh "npm run build:ssr"
  }
  stage('Deploy'){
    sh "pm2 restart all"
  }
}
