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
     
* Modular Pipeline is basically the combibation of Parameterization and Variablization. 
* Modularization helps the user to be more precise in writing and segregating the code. 
* We can segregate the stages according to the requirement.
* Modular Pipeline yaml file consists of two stages i.e "Sonarqube Code Analysis" and "Static Scan with ASoD"

![image](https://user-images.githubusercontent.com/95271479/210701829-84f9c3f3-28b1-40f8-af6c-3ea158b8deb0.png)







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


  
  
  


  
  
  
  
  


      


     
