pipeline{
    agent any


    stages{
        stage('Build'){
            steps{
                sh 'mvn -B -DskipTests clean package'
            }
        }
        stage('Test'){
            steps{
               sh 'echo "test stage"'
            }
        }
        stage("deliver"){
            steps{
                sh 'echo "deliver stage"'
            }
        }
    }
}
