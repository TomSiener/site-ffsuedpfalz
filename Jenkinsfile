node {
    /* .. snip .. */
    stage('Build') {
        deleteDir()
        echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
        echo "Branch: ${env.BRANCH_NAME}"
        checkout scm
        sh "sh -x ${WORKSPACE}/build-jenkins.sh"
    }
}
