pipeline
{
  agent any
  stages
 {
   stage("checkout_source_code")
    {
     steps
      {
         git branch: 'feature1', url: 'https://github.com/devaraj-2604/MultibranchPipelinenew.git'
      }
     }
    stage("checkoutfor_keyword")
     {
      steps
       {
         sh 'cat index.html | grep -i healthcare'
       }
     }
 }
}
