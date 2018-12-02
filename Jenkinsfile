pipeline {
    agent any

    stages {
    stage ('Display s3') {

                        steps {

                                sh 'aws s3 ls'

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
