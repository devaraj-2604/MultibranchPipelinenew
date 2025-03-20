pipeline
{
  agent any
  stages
 {
   stage("checkout_source_code")
    {
     steps
      {
         git branch: 'feature3', url: 'https://github.com/devaraj-2604/MultibranchPipelinenew.git'
      }
     }
    stage("checkoutfor_keyword")
     {
      steps
       {
         sh 'cat contact.html | grep -i healthcare'
       }
     }
 }
}
