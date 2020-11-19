pipeline{
    agent any
    stages{
        stage('Clean'){
            steps{
                echo "Clean Stage"
                mvn clean
            }
        }
        stage('Test'){
            steps{
                echo "Test Stage"
                mvn test
            }
        }
        stage('Package'){
            steps{
                echo "Package Stage"
                mvn package
            }
        }
        // stage('Deploy'){
        //     steps{
        //         echo "Deploy Stage"
        //         mvn deploy
        //     }
        // }
    }
}