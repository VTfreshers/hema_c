pipeline
{
    agent any
    stages
    {
      stage ("fetching code")
      {
        steps
        {
          git 'https://github.com/VTfreshers/hema_c.git'
        }
      }
      stage ("building")
      {
        steps
        {
            cmakeBuild buildDir: 'build', installation: 'InSearchPath', sourceDir: '/var/lib/jenkins/workspace/hema_c'
        }
      }
    }
}
