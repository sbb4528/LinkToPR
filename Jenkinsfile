node {
  stage ('Development') { echo 'Dev' }
  stage ('Testing') { echo 'QA' }
  stage ('Production') { echo 'Live' }
}
def jobName = "${env.JOB_NAME}"
GIT_COMMIT = sh (
script: 'git rev-parse HEAD',
returnStdout: true
).trim()
echo "Git committer email: ${GIT_COMMIT}"
currentBuild.description = "<a href='https://github.com/sbb4528/LinkToPR/commit/$GIT_COMMIT_EMAIL'>PR</a>"
Jenkins.instance.getItem(jobName.split('/')[0]).description = "<a href='https://github.com/sbb4528/LinkToPR/commit/$GIT_COMMIT_EMAIL'>HEllo</a>"
