pipeline
       {
        agent any
            stages
                 {
                 stage("Git")
                      {
                      steps
                        {
                        git "https://github.com/Dwaraka224/mar2_jenkins_task.git"
                        }
                      }
                        stage("Run")
                            {
                            steps
                         {
                               sh "java Demo.java"
                               }
                             }
}
 }
  
