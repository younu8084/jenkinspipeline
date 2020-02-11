@Library('shlib1')_
pipeline{
  agent any
  stages{
     stage('jenkins')
            {
                steps
                  {
                    lastsuccessfulbuild()
                    lastfailurebuild()
                  }
            }
  }
}
