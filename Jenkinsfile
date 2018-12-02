pipeline {
    agent any

    stages {
    stage ('Display s3') {

                        steps {

                                sh 'echo $PATH'

                        }
                        }
        stage ('Display Direcotry') {

                    steps {

                            sh 'pwd'

                    }
                    }

        stage ('Compile Stage') {

            steps {

                    sh 'mvn clean compile'

            }
        }

        stage ('Testing Stage') {

            steps {

                    sh 'mvn test'

            }
        }


    }
}
