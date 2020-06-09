pipeline {
    agent any
    options {
        ansiColor('xterm')
        timestamps()
        timeout(time: 1, unit: 'HOURS')
    }

    parameters {
        string(name: 'REF', defaultValue: '\${sha1}', description: 'Commit to build')
    }

    stages {
        stage('Test') {
            steps {
                echo 'Hello World!'
                sh 'exit 1'
            }
        }
    }
}
