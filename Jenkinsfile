node {
  stage ('Development') { echo 'Dev' }
  stage ('Testing') { echo 'QA' }
  stage ('Production') { echo 'Live' }
}
//def jobName = "${env.JOB_NAME}"
//echo jobName.split('/')[0]
def description = "<a href='https://github.snei.sony.com/sbolleddu/Multibranch-ci-test/pulls/$PULL_REQUEST_NO'> Hello </a>"
currentBuild.setDescription(description)
//Jenkins.instance.getItem(jobName.split('/')[0]).getItem("${env.BRANCH_NAME}").description = "<a href='https://github.com/sbb4528/LinkToPR.git'> Hello </a>"
