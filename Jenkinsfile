pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        // You can add more stages here as needed
    }

    // You can also define post-build actions or other sections here if necessary
}
