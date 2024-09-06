pipeline {
    agent any
    environment {
        NAMES = "STAN"
    }

    stages {
        stage("Datascientest Env Variables") {
            steps {
                echo "The build id is ${env.NAMES} "
            }
        }
    }
}