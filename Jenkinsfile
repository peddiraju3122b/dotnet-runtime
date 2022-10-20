pipeline{
    agent {label 'UBUNTUNODE'}
    stages{
        stage('git clone'){
            steps{
                git url : 'https://github.com/peddiraju3122b/dotnet-runtime.git',
                branch : 'main'
            }
        }
        stage('dotnetbuild'){
            steps{
                sh 'dotnet build'
            }
        }
    }
    
}