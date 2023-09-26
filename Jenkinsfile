pipeline {
   agent any
  //   {
  //    node {
  //        label 'docker-agent-python'
  //        }
  //  }
    triggers {
        pollSCM '* * * * *'
    }
    stages {
        stage('Build') {
            steps {
                echo "Building.."
 //               sh '''
 //               pip install -r requirements.txt
 //              '''
            }
        }
        stage('Test') {
            steps {
                echo "Testing.."
  //              sh '''
  //              python3 helloworld.py
  //              python3 helloworld.py --name=Brad
  //              '''
            }
        }
        stage('Deliver') {
            steps {
                echo 'Deliver....'
                sh '''
                echo "doing delivery stuff.."
                '''
            }
        }
    }
}
