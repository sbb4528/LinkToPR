def jobName = "${env.JOB_NAME}"
def PULL_REQUEST_NO = "${env.PULL_REQUEST_NO}"
def description = "<a href='https://github.com/sbb4528/LinkToPR/pulls/$PULL_REQUEST_NO'> PR </a>"
currentBuild.setDescription(description)
Jenkins.instance.getItem(jobNa me.split('/')[0]).description = "<a href='https://github.com/sbb4528/LinkToPR/pulls/$PULL_REQUEST_NO'> Hello </a>"
node {
  stage ('Development') { echo 'Dev' }
  stage ('Testing') { echo 'QA' }
  stage ('Production') { echo 'Live' }
}
