The DevOps repository consists automated CICD pipleline. The pipeline is maninly designed to understand the various features of jenkins.

![image](https://user-images.githubusercontent.com/95271479/210701695-4468f704-4123-4de4-a618-dd9693538072.png)





     
   
___________________________________________________________________________________________________________________________________________________________________
PREREQUISITES

1) Jenkins instance
2) ASoD instance

_____________________________________________________________________________________________________________________________________________________________________
     FEATURES IN JENKINS
 
1) Modular pipeline
2) Variablization
3) Parameterization


 _____________________________________________________________________________________________________________________________________________________________________
     MODULAR PIPELINE
     
* Modular pipeline is logically isolated and can be reused. Modular pipelines are easier to develop, test and maintain, and are portable so they can be copied and reused between projects.

* This Modular Pipeline is Variablised and Parametrised.







______________________________________________________________________________________________________________________________________________________________________
      PARAMETERIZATION
      Parameterization help to control the portion of the test to be executed. Here, in this modular pipeline we are using boolean paramter.
      Hence by defining Boolean Parameter inside a jenkins pipeline we can trigger the "Build with Paramaters" option.
      
  ![image](https://user-images.githubusercontent.com/95271479/210701613-8b04a423-8721-450c-a78f-9a04b49bbd8b.png)





      
___________________________________________________________________________________________________________________________________________________________________

      VARIABLIZATION
      Pipeline Variablization helps to separate configuration values from the core and inject during the runtime. Variablization is done for ASoD and sonarqube.
      Keep the groovy file which contains variables, and load the variables from the github into the pipeline during the runtime.
      
  ![Capture](https://user-images.githubusercontent.com/95271479/210702011-69d33082-8bee-4bd5-8748-ed09bfa3cbf5.JPG)
  
  

___________________________________________________________________________________________________________________________________________________________________

PIPELINE VIEW

* Pipeline has two stages Checkout and ASoD
* Checkout stage will get the latese source code from GitHub repository.
* ASoD stage initiates the security scan.

<img width="602" alt="asod-mod" src="https://user-images.githubusercontent.com/52232710/212962784-014be1d8-e298-4430-816b-b772bde673cd.PNG">


  
  
  


  
  
  
  
  


      


     
