TT_IS_MASTER = env.JOB_NAME == "verify-ios-pr-bryan-test"

// We don't allow parallel runs of PR verification jobs to avoid one person putting too much load on
// jenkins
if (!TT_IS_MASTER) {
  properties([disableConcurrentBuilds()])
} else {
  properties()
}

node() {
    echo 'hello there 1'
    sleep(30)
    echo 'hello there 2'
}
