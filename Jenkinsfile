pipeline {
    agent any

    stages {
        stage ('Stg1'){
            steps {
                echo "Step 1"
            }
        }
        stage ('Stg2'){
            parallel
            {
                stage("2.1"){
                    steos {
                        echo "This is step 2.1"
                    }
                }
            }
        }
    }
}