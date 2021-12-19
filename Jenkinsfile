pipeline {
    agent {
        label 'slave_1'
    }
    stages {

    stage ('checkout')
    {
        steps
        {
            checkout scm
        }
    }
    stage ('sucessfull excution')
    {
        steps {
            echo "checkout has been done"
        }
    }
    }
}
