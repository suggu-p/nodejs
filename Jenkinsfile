
node("launchpad-nodejs") {
  checkout scm
  stage("BuildCode") {
    sh "npm install"
  }
  stage("Deploy") {
    sh "npm run openshift"
  }
}
