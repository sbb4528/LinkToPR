//def jobName = "${env.JOB_NAME}"
//echo jobName
//def PULL_REQUEST_NO = "${env.PULL_REQUEST_NO}"
//def PR_NO = "${env.CHANGE_ID}"
//echo PR_NO
//def description = "<a href='https://github.com/sbb4528/LinkToPR/pulls/PR_NO'> PR </a>"
//echo description
//currentBuild.setDescription(description)
currentBuild.description = "<a href='https://github.com/sbb4528/LinkToPR/pulls/$env.CHANGE_ID'> Hello </a>"
//Jenkins.instance.getItem(jobName.split('/')[0]).description = "<a href='https://github.com/sbb4528/LinkToPR/pulls/PR_NO'> Hello </a>"
//def description = "<a href='https://github.snei.sony.com/sbolleddu/Multibranch-ci-test/pulls/$PULL_REQUEST_NO'> PR </a>"
//currentBuild.setDescription(description)

node {
  stage ('Development') { echo 'Dev' }
  stage ('Testing') { echo 'QA' }
  stage ('Production') { echo 'Live' }
}
