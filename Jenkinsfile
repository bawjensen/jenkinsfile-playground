TT_IS_MASTER = env.JOB_NAME == "ios"

// We don't allow parallel runs of PR verification jobs to avoid one person putting too much load on
// jenkins
if (!TT_IS_MASTER) {
  properties([disableConcurrentBuilds()])
}

node() {
    echo 'hello there 1'
    sleep(30)
    echo 'hello there 2'
    echo 'hello there 3'
}
