
@Library("jenkins-integrated@master") _

pipeline {
    agent any
    stages {
        stage('Git Checkout') {
            steps {
            gitCheckout(
                branch: "master",
                url: "https://github.com/deepshikharai/phptest.git"
            )
            }
    }
    }
}