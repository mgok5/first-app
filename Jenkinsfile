pipeline{

    agent any
    environment {
        PATH = "C:\Program File\Git\usr\bin:$PATH"
    }
    stages{

        stage('Git checkout'){

            steps{
                git branch: 'main', url: 'https://github.com/mgok5/first-app.git'
            }
        }

        stage('UNIT Testing'){

            steps{
                sh 'mvn test'
            }
        }
    }
}