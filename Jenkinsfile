@Library('shlib1')_
pipeline{
  agent any
  stages{
     stage('update_Proj')
            {
                steps
                 { 
                    bbupdatedeployproject(JSON)
                    bbnewlog("name updated successfully for the deployment project")
                    }
                    post{
                          failure{
                               bbnewlog("name is not updated successfully for the deployment project")
                                  }
                        }
                 }
                 
                 
            
              stage('add label')
            {
                steps
                 { 
                    bbaddlabelbuild(JSON)
                    bbnewlog("label added successfully for the project")
                    }
                     post{
                       failure{
                             bbnewlog("label not added successfully for the project")
                                }
        
                        }
                    }
                    }
                    }
