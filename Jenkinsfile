@Library('shlib1')_
pipeline{
  agent any
  stages{
     stage('update_Proj')
            {
                steps
                 { 
                    bbupdatedeployproject(JSON)
                    bblog("name updated successfully for the deployment project")
                    }
                    post{
                          failure{
                               bblog("name is not updated successfully for the deployment project")
                                  }
                        }
                 }
                 }
                 }
            }
              stage('add label')
            {
                steps
                 { 
                    bbaddlabelbuild(JSON)
                    bblog("label added successfully for the project")
                    }
                     post{
                       failure{
                             bblog("label not added successfully for the project")
                                }
        
                        }
                    }
                    }
                    }
