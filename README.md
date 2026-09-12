## Tripot---Personalised-Trip-Planner
A travel planning app where users can plan trips, create vision boards, and get personalized destination recommendations based on their top three hobbies and their budget.

## Core Concept
A website where users:
- Plan trips
- Create travel vision boards with mood boards, images, goals (In progress)
- Create their Budget
- Create the itinerary
- Create a checklist 
- Accessible UI for all users

## Programming
- Front-End: React, CSS, HTML, JavaScript 
- Figma Designs : 3 screens: Dashboard, Vision Board, Trip Recommender. 

## Git Development Process
1. Verify that you're in the main branch.
    ```sh
    git branch
    ```
2. Make sure your main branch is up to date by doing the following command.
    ```sh 
    git pull
    ```
3. Create a branch off of the main branch with the issue number as the prefix, followed by the title or summary of the issue. Then checkout that branch.
    ```sh
    git checkout -b 2-create-navbar
    ```
4. If you created new files, add them through the following command.
    ```sh
    git add --all
    ```
5. Save your changes. Inside the quotation marks, put the commit message which describes the changes you made.
    ```sh
    git commit -m "Create navigation bar."
    ```
6. To push the code: 
    ```sh
    # if pushing for the first time:
    git push --set-upstream origin <branch-name>

    # otherwise do:
    git push 
    ```
7. Creatinh a pull request on GitHub. 
    - Go to Pull Requests tab, New Pull Request. 
    - Keep the `base:main`, change the `compare:<branchName>` to your branch. 
    - Review your changes and create the pull request.
    - Add "closes #2" (#2 being the issue number) in the description so it automatically closes the issue once the pull request has been merged.
8. Wait for approval, fix merge conflicts if necessary, then merge.
