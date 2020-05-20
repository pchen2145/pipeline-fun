@Library('jenkins-shared-library@master') _

pipeline {
    agent any
    stages {
        stage('Checkout from Git') {
            steps {
            gitCheckout(
                branch: "master",
                url: "https://github.com/pchen2145/springbootmaven.git"
            )
            }
        }
    }
}
added line simulation
