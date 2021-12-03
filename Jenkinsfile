pipeline {
    parameters {
        choice(
            name: 'VERSION',
            description: 'Choose the version of the project',
            defaultValue: '1.0',
            choices: ['1.0', '2.0', '3.0']
        )
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building the project'
            }
        }

        stage('Version Print') {
            steps {
                echo 'Printing the version'
                echo "${VERSION}"
            }
        }
    }
}