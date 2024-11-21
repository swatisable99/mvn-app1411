pipeline{
    agent{
        label('maven-build-servre')
    }
    tools{
        maven 'maven-3.9.8'
    }
    stages{
        stage('Code Build Stage'){
            stage{
                mvn install
            }
        }
    }
}