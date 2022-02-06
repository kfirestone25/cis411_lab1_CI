# Lab Report: Continuous Integration
___
**Course:** CIS 411, Spring 2022  
**Instructor(s):** [Trevor Bunch](https://github.com/trevordbunch)  
**Name:** Kylie Firestone  
**GitHub Handle:** kfirestone25  
**Starred Repository:** https://github.com/flutter/flutter  
**My Forked Repository:** https://github.com/kfirestone25/cis411_lab1_CI 
___

# Step 1: Fork this repository
- The URL of my forked repository: https://github.com/kfirestone25/cis411_lab1_CI 
- The accompanying diagram of what my fork precisely and conceptually represents...
  
![ForkDiagram](https://docs.google.com/drawings/d/e/2PACX-1vQjfCOIqMcQTjSUloU09xKnwXVVaqSUv2_cJQwweYv58J2xI3eJEv7GW2Jlm24WlJLtimy2xMQUFKRL/pub?w=962&h=634)

# Step 2: Clone your forked repository from the command line  
- My local file directory is...
- The command to navigate to the directory when I open up the command line is...

# Step 3: Run the application locally
- My GraphQL response from adding myself as an account on the test project
``` json
{
  "data": {
    "mutateAccount": {
      "id": "4b365fa5-455f-43b9-bdf5-ad80ccaa689a",
      "name": "Kylie Firestone",
      "email": "kf1322@messiah.edu"
    }
  }
}
```

# Step 4: Creating a feature branch
- The output of my git commit log
```
Insert the logs here.
```
- The accompanying diagram of what my feature branch precisely and conceptually represents...

# Step 5: Setup a Continuous Integration configuration
- What is the .circleci/config.yml doing?  


- What do the various sections on the config file do?  
   

- When a CI build is successful, what does that philosophically and practically/precisely indicate about the build?  
   

- If you were to take the next step and ready this project for Continuous Delivery, what additional changes might you make in this configuration (conceptual, not code)?  
   

# Step 6: Merging the feature branch
* The output of my git commit log
```
Trevors-MBP:cis411_lab0 trevorbunch$ git log --oneline
dbf826a (HEAD -> labreport, origin/labreport) Answer Step 4
a9c1de6 Complete Step 1, 2 and 3 of LAB_TREVORDBUNCH
1ead543 remove LAB.md
8c38613 Initial commit of labreport with @tangollama
dabceca (upstream/main, origin/main, origin/HEAD, main) Merge pull request #24 from tangollama/circleci
a4096db Create README.md
...
44ce6ae Initial commit
(END)
```

* A screenshot of the _Jobs_ list in CircleCI
![CircleCI Success](../assets/circleci_success.png)
