pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Harish"'
                sh '''
                    bazel build //src:hi
                    echo "Multiline shell steps works too"
                '''
            }
        }
    }
}
