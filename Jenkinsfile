pipeline
{
  agent any
  stages
 {
   stage("checkout_source_code")
    {
     steps
      {
         git branch: 'feature2', url: 'https://github.com/devaraj-2604/Multibra>
      }
     }
    stage("checkoutfor_keyword")
     {
      steps
       {
         sh 'cat about.html | grep -i healthcare'
       }
     }
 }
}
