# Documentation of project 14

1. I logged into my jenkins console and installed "blue ocean"
   
   ![Project14](images/project1.PNG)
   ![Project14](images/project2.PNG)

2. I opened the blue ocean and created a pipeline
   ![Project14](images/project3.PNG)
   ![Project14](images/project4.PNG)
   ![Project14](images/project5.PNG)
   ![Project14](images/project6.PNG)
   ![Project14](images/project7.PNG)

3. I created a new directory and named it 'deploy'

4. Then I created a jenkins file in the deploy directory
   
   ![Project14](images/project8.PNG)

5. I inserted some commands in the jenkins file

   ![Project14](images/project9.PNG)

6. I pushed it to my github account
    
    ![Project14](images/project10.PNG)

7. I configured my ansible project on jenkins console
    
    ![Project14](images/project11.PNG)
    ![Project14](images/project12.PNG)
    ![Project14](images/project13.PNG)

8. I clicked on build and went to check my pipeline
    ![Project14](images/project14.PNG)

9. I created switched to a new branch called "feature/jenkins-pipeline-stages"
    
    ![Project14](images/project15.PNG)
    ![Project14](images/project16.PNG)

10. I added another stage to my jenkins file, pushed it and scanned the repository

    ![Project14](images/project17.PNG)
    ![Project14](images/project18.PNG)
    ![Project14](images/project19.PNG)

11. I created a pull request

    ![Project14](images/project20.PNG)

12. I added new stages to my jenkins file, pushed it and scanned it.

    ![Project14](images/project21.PNG)
    ![Project14](images/project22.PNG)
    ![Project14](images/project23.PNG)
    ![Project14](images/project24.PNG)
    ![Project14](images/project25.PNG)
    ![Project14](images/project26.PNG)

13. I installed ansible
   
   ![Project14](images/project27.PNG)
   ![Project14](images/project28.PNG)

14. I installed postgresql community

    ![Project14](images/project29.PNG)

15. I installed the required dependencies

    ![Project14](images/project30.PNG)
    ![Project14](images/project31.PNG)
    ![Project14](images/project32.PNG)
    ![Project14](images/project33.PNG)

16. I installed ansible on my jenkins console
    
    ![Project14](images/project34.PNG)
    ![Project14](images/project35.PNG)

17. I add my private key to the global credentials on jenkins console

    ![Project14](images/project36.PNG)

18. I configured my pipeline syntax and got my parameters
    
    ![Project14](images/project37.PNG)

19. I ran my ansible command and it worked fine
    
    ![Project14](images/project38.PNG)
    ![Project14](images/project39.PNG)
    ![Project14](images/project40.PNG)
    ![Project14](images/project41.PNG)
    ![Project14](images/project42.PNG)
    ![Project14](images/project43.PNG)
    ![Project14](images/project44.PNG)
    ![Project14](images/project45.PNG)
    ![Project14](images/project46.PNG)
    ![Project14](images/project47.PNG)
    ![Project14](images/project48.PNG)
    ![Project14](images/project49.PNG)
    ![Project14](images/project50.PNG)

20. In my ansible execution section, I removed "inventory/dev" and replaced it with  "${inventory}" so I will be able to pick any file in inventory on the pipeline

     ![Project14](images/project51.PNG)
     ![Project14](images/project52.PNG)
     

21. I forked a repository that was given
   
    `https://github.com/darey-devops/php-todo.git`
     
     ![Project14](images/project53.PNG)

22. Then I cloned the repository "php-todo"
   
    ![Project14](images/project54.PNG)

23. I installed php and it's dependencies

    ![Project14](images/project55.PNG)
    ![Project14](images/project56.PNG)
    ![Project14](images/project57.PNG)
    ![Project14](images/project58.PNG)

24. I installed 'plot' on jenkins console
    
    ![Project14](images/project59.PNG)
    ![Project14](images/project60.PNG)

25. I installed 'artifactory' also on jenkins console

    ![Project14](images/project61.PNG)
     ![Project14](images/project62.PNG)

26. I configured it and ran my playbook

    ![Project14](images/project63.PNG)
    ![Project14](images/project64.PNG)
    ![Project14](images/project65.PNG)
    ![Project14](images/project66.PNG)
    ![Project14](images/project67.PNG)

28. I logged int my instance to confirm if mysql has been installed
    
    ![Project14](images/project68.PNG)
    ![Project14](images/project69.PNG)

29. I created another jenkins file in my php-todo directory, added some stages and ran the code
  
     ![Project14](images/project70.PNG)
     ![Project14](images/project71.PNG)
     ![Project14](images/project72.PNG)
     ![Project14](images/project73.PNG)

30. Plots was succesfully installed in my php branch on jenkins console
    
    ![Project14](images/project74.PNG)

31. I uploaded artifactory successfully
    
    ![Project14](images/project75.PNG)
    ![Project14](images/project76.PNG)

32. I created another stage to deploy to dev environment
    ![Project14](images/project77.PNG)
    ![Project14](images/project78.PNG)

33. I exported the ansible.cfg file
    
    ![Project14](images/project79.PNG)

34. Then I ran the playbook again and it worked

    ![Project14](images/project80.PNG)
    ![Project14](images/project81.PNG)
    ![Project14](images/project82.PNG)
    ![Project14](images/project83.PNG)
    

35. I checked my sonarqube server
    
    ![Project14](images/project84.PNG)

36. I installed sonarqube scanner on jenkins console and configured it
    
    ![Project14](images/project85.PNG)
    ![Project14](images/project86.PNG)

37. I created a webhook on my sonarqube server
    
    ![Project14](images/project87.PNG)
    ![Project14](images/project88.PNG)

38. I created a step but it failed because I didn't update scanner properties

    ![Project14](images/project89.PNG) 

39. I updated the scanner properties then I ran it successfully
    ![Project14](images/project90.PNG)
    ![Project14](images/project91.PNG)

40. I introduced jenkins agent
    
    ![Project14](images/project92.PNG)

41. I configured webhook between jenkins and github to automatically run the pipeline when there is a push
    
    ![Project14](images/project93.PNG)