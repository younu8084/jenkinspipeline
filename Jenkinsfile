@Library('shlib1')_
pipeline{
  agent any
  stages{
     stage('jenkins')
            {
                steps
                  {
                    lastsuccessfulbuild(bamboo1)
                    lastfailurebuild(bamboo1)
                  }
            }
  }
