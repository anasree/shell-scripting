pipeline{

  agent any

    stages{

      stage('Setup'){

        steps {
          echo "Hello Ansible"
          sh "date"
        }
      }

      stage('Configure'){
        steps {
          sh "cp Jenkinsfile test.txt"
        }
      }
    }
}
