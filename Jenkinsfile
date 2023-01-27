pipeline{

    agent any

    stages{

        stage('Git checkout'){

            steps{
                git branch: 'main', url: 'https://github.com/mgok5/first-app.git'
            }
        }

        stage('UNIT Testing'){

            steps{
                bat 'mvn test'
            }
        }
    }
}