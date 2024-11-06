pipeline {
agent any 
stages
{  stage ('my first job to print')
   {steps {sh 'echo hello_jenkins'}} 
}
   
{  stage ('build')
   {steps {sh 'echo build the job'}} 
}
{ stage ('deploy')
   {steps {sh 'echo deploy the job'}}
}
}
