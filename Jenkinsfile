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

    stage('Equipment') {
      steps {
        echo 'Get to know your seat'
        echo 'Unbox laptop'
        echo 'Set up monitors/docking station'
      }
    }

    stage('Gmail Registration') {
      steps {
        echo 'Perform first login and set up 2FA'
      }
    }

    stage('Services Registration') {
      steps {
        echo 'Slack'
        echo 'LastPass'
        echo 'Trello'
      }
    }

    stage('Services Intro /w TL') {
      steps {
        echo 'Overview of usage conventions'
      }
    }

    stage('10bis') {
      steps {
        echo 'Get 10bis card from HR office'
      }
    }

    stage('Software Installation') {
      parallel {
        stage('Chrome') {
          steps {
            echo 'Install Chrome'
          }
        }
        
        stage('Git') {
          steps {
            echo 'Install Git'
          }
        }
        
        stage('Python') {
          steps {
            echo 'Install Python 2.7'
            echo 'Install Python 3 latest'
          }
        }
        
        stage('Visual Studio') {
          steps {
            echo 'Install VS including Win10 SDK and Debugging tools'
            echo 'Make sure WindDbg is working'
          }
        }
      }
    }
  }
}
