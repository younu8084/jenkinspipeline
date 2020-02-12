@Library('shlib1')_
pipeline{
  agent any
  stages{
     stage('jenkins')
            {
                steps
                  {
                    //lastsuccessfulbuild(JSON)
                   // moveinflux(JSON)
                  //  azurecollect()
                  //  azureinflux()
                  //  repo()
                    lastfailurebuild()
                    moveinflux()
                    
                  }
            }
  }
}
