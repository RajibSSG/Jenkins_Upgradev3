pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Rajib'
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area Environment"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production System"
                  }
			stage('Deploy Contingency') {
                  steps {
                        echo "Deploying in Contingency System"
                  }				  
				}  
				  
            }
      }
}