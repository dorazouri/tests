pipeline {
  agent any
  stages {
    stage('Contract') {
      steps {
        echo 'Sign Contract'
        echo 'Sign stock options terms'
      }
    }

    stage('Pre Boarding') {
      parallel {
        stage('Literature') {
          steps {
            echo 'Read python book'
            echo 'Browse the team\'s twitter lists'
            echo 'Read provided articles'
          }
        }

        stage('Office Visit') {
          steps {
            echo 'Meet VP R&D'
            echo 'Meet TL'
            echo 'Get parking tickets'
          }
        }

        stage('HR') {
          steps {
            echo 'Call with HT representative'
            echo 'Send passport photo'
            echo 'Send contact details'
          }
        }

      }
    }

  }
}