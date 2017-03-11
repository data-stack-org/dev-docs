# Working with diagrams

For creating a diagram it's recommended to use [draw.io](https://www.draw.io) web application. The current guide describes the process of creating and editing diagrams in draw.io application.

## Creating a diagram

1. Create new feature branch under your repository (for example `feature/provide-use-case-diagram`).
2. Make sure that directory structure for the future diagram is prepared (for example new `Use Case Diagram.xml` file will be in the `dev-docs/diagrams` directory).
3. Open [draw.io](https://www.draw.io) web application in your web browser.
4. If you've authorised in draw.io before, close the pop-up and go to step #8.
5. In the *Save diagrams to* pop-up click *Decide later* button in the bottom. We'll configure saving in further steps.
6. Go to *File > New...* menu to create new diagram.
7. Enter the name of your new diagram in the *Filename* input. If you don't prefer to draw your diagram from predefined template choose *Blank Diagram* under *Basic* section and press *Create* button.
8. Now you are able to draw the diagram in the draw.io environment. See more about the [draw.io environment](https://support.draw.io/display/DO/The+draw.io+Environment) and [creating diagrams](https://support.draw.io/display/DO/Tutorial+1+-+Creating+a+Diagram).
9. When the drawing is finished and is ready for publishing, go to *File > Save as...*.
10. In the opened pop-up enter the diagram's file name (for example *Use Case Diagram.xml*).
11. Choose *GitHub* option.
12. If you've authorised in draw.io before, go to step #15.
13. In the *Authorization required* pop-up press *Authorise* to authorise draw.io application using your GitHub account.
14. Enter your GitHub credentials in the new opened window and press *sign in*.
15. In the *Select Folder* pop-up you'll see a list of repositories available to save new diagram.
16. After selecting the repository you'll be asked to choose folder under it.
17. Choose the branch created in the first step (in our example it is `feature/provide-use-case-diagram`) by clicking on master branch (you should see something similar to this `<username>/<repository_name> / master`).
18. In the opened branch list choose your feature branch.
19. Select directory to save the diagram and press *OK* button.
20. In the opened pop-up enter commit message and press *OK* button.
21. Go to your repository to make sure that file *Use Case Diagram.xml* file is created in the `dev-docs` repository in the `diagrams` directory and under the `feature/provide-use-case-diagram` branch.
22. To get a link to created diagram go to *File > Export as > URL...*. In the opened pop-up leave default options and press *Create*. In the next opened pop-up link to current diagram will be provided.

> When creating a new Pull Request that contains diagrams, always provide the link to diagrams in the comment under that Pull Request.

## Editing a diagram

1. Open [draw.io](https://www.draw.io) web application in your web browser.
2. In the *GitHub* pop-up choose *Open Existing Diagram*.
3. In the *Select Folder* pop-up chose repository in which you want to find a diagram file.
4. Choose branch you are working on (`master` branch is used by default).
5. Find and open diagram file in the directory structure.
6. Now your diagram is loaded and you are able to continue to work with it.
7. Before making changes save a link to current version of the diagram. Go to *File > Export as > URL...* menu to get the URL of current diagram snapshot and save it. We'll use it later for comparing with updated version of the current diagram.
8. When editing diagram is finished save your changes. Go to *File > Save* to push updated diagram to your repository. You'll be asked to enter commit message before saving.
9. Repeat step #7 to get URL of latest drawing snapshot.

> If you update Pull Request that contains diagrams, always provide the comment with links to previous and updated versions of diagrams respectively.
>
> For more information about working with draw.io web application visit official [Draw.io Online User Manual](https://support.draw.io/display/DO/Draw.io+Online+User+Manual).
