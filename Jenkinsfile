node {
    print "Hello $(env.BRANCH_NAME)!"
    checkout scm
    echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
    /* .. snip .. */
    stage('Build') {
        echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
        
    }
    /* .. snip .. */
}
