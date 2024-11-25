pipeline{
    agent{
        node{
            label 'maven_build_server'
        }
    }
    tools{
        maven 'maven-3.9.8'
    }
    stages{
        stage('Code Build Stage') {
            steps{
               sh 'mvn install -Dmaven.test.skip=true'
            }
        }
    }
}
