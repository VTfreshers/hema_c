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
          cmake sample.c
        }
      }
    }
}
