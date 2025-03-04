pipeline
{
  agent {label 'sandeep'}
   parameters 
{
  choice choices: ['master', 'ravitejareddy'], description: 'picksomething', name: 'choice'
}
  stages
   {
       stage('1')
        {
           steps
          {
           sh 'git clone https://github.com/RavitejaAdepudi/javawar.git'
          }
        }
   }


  
}
