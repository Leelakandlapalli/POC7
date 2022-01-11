pipeline {
    agent any
 stages {
    stage('Build branch') {
            when{
                expression {branch=='Build'}
            }
            steps {
                echo 'Build is successful'
            }
        }
        stage('Test branch'){
            when{
                expression{branch=='Test'}
            }
            steps{
                echo"Testing is successful"
            }
        }
        stage('deploy branch'){
            when{
                expression{branch=='Deploy'}
            }
            steps{
                echo"Deployment is successful"
            }
        }
    }
}
