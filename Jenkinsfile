node {
  stage ('Development') { echo 'Dev' }
  stage ('Testing') { echo 'QA' }
  stage ('Production') { echo 'Live' }
}
def PULL_REQUEST_NO = "${env.PULL_REQUEST_NO}"
def description = "<a href='https://github.snei.sony.com/sbolleddu/Multibranch-ci-test/pulls/$PULL_REQUEST_NO'> Hello </a>"
currentBuild.setDescription(description)
