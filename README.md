# **Vacation Picker Mobile Application**
*Course: D308 - Mobile Application Development*
*Author: Anthony Roth*
___
### Purpose of the Application
> This application allows users to plan vacations and excursions according to their individual scheduling and travel needs.
___
### Rubric Showcase
**Rubric Step A: GitLab Repository**
> Subgroup and Project Created:
![StepA1-Subgroup](/docs/img/StepA1-SubGroup.PNG)

> GitLab Link: https://gitlab.com/wgu-gitlab-environment/student-repos/aroth35/d308-mobile-application-development-android.git

> Android Target APK Version: #31

**Rubric Step B1: Functional Requirements**
> First, install the APK on any android device that supports apk version 31 or higher.
> Second, launch the application. This will bring you to a new screen with an Enter button in the center.
Click this button and you will be greeted with the Vacation List Screen.
Once there, any vacations you have created previously will show up as a list. Clicking these vacations allows you to edit them if you so choose. If there are no vacations shown this means none have been created yet.
> On the bottom right corner of the screen there is a plus symbol button. Clicking this button will allow you to create a new vacation.
> **(Note: If the vacation has an excursion associated with it, deletion will not be possible until the excursion is deleted first.)

**Rubric Step B2, B3A, & B3B: Vacation Details, implementation, and editing**
> After clicking on the plus button or one of the vacations in your list, you will be brought to the vacation details screen. The details will be shown and ready to edit if you chose to edit an existing vacation. Otherwise, the details will be blank.
> Using the text fields, users can add a title, and hotel for their vacation. In addition, users can use the start date/end date buttons to choose the vacation timeframe.
> On the top right of the screen, an ellipsis is shown. Use this to save/update, delete, set a text alarm for the vacation start/end dates, or copy the vacation details(excursion details included if an excursion is associated with the vacation).
> As for the plus button on the bottom right of the screen, use this button to create a new excursion. When going back to edit the vacation, any associated excursions will appear in a list in the space below the start/end dates.

**Rubric Step B3C: Vacation Date Validation**
> If you attempt to set the end date before the start date, the user will be notified via a toast that the end date must be after the start date. The date shown on the button will then reverse itself back to it's original text/value and it will not be set. Saving your vacation at this point may not be possible if no acceptable values are given for the start/end dates (this includes leaving the values blank).

**Rubric Step B3E: Vacation Alert**
> If the user wishes to be notified when their vacation is starting, ending, or both, click the ellipsis on the top right of the screen and choose the option, "Set Alarm".
(Keep in mind that this option will toast the user if the vacation is not saved yet. Same goes for all other options in the ellipsis list).
Choosing this option allows the user to choose to receive a notification when the vacation is starting, ending, or for both.
Some users may not want to be told when it's ending or have already started their vacation, so the choice is theirs to make. Once you have chosen your option, a notification will be triggered and sent on the date/s/ chosen.

**Rubric Step B3F: Sharing Features**
> Users can also share details of their vacation once it's saved. First, click the ellipsis on the top right of the screen, then choose the "Copy Vacation Data" option. This will copy the details of the vacation and any associated excursions to the users clipboard. After this the user can share details or save them in a note for later.

**Rubric StepB3G, B3H & B4: Excursions, Editing, & Excursions For Each Vacation**
> Once the vacation is saved users can add new excursions or edit associated ones.

> To create a new excursion, click the plus symbol on the bottom right of the screen. This will bring the user to the Excursion Details screen. Once on this screen, the user will see a title text field, and a start date button.
The user can use the text field and date button to type the title of the excursion and choose a date for the excursion. If the date chosen is outside of the vacation timeframe, the user will receieve a toast indicating they must choose a date within the vacation timeframe. Until a correct date is chosen, the excursion will not be saveable.
Once the user enters correct data, they can choose to save or delete the excursion using the ellipsis on the top right of the screen.
**(Note: attempting to delete an excursion without saving will inform the user that the excursion must be saved to be deleted.)

> To edit an existing excursion, on the vacation details screen, click on the excursion you wish to edit.
Once on the excursion details screen, the data associated with the excursion will fill up the text field and date respectively. From here the user can alter the details, save, or choose to delete the excursion entirely.

**Rubric Step B5: Interface Requirements**
1. The application displays a detailed view of the excursion, which includes the title and date.
2. The application allows users to enter, edit, and delete excursion information.
3. The application includes validation that the input dates are formatted correctly.
4. The application includes an alert that the user can set. This alert is triggered on the excursion date and states the excursion title.
5. The application includes validation to make sure the excursion date is set during the associated vacation timeframe.

**Rubric Step C: Screen Layouts**
> The screen designs include the layout for each given screen, as described, and includes appropriate GUI elements for each layout.

**Rubric Step D: Storyboard**
> The included storyboard demonstrates the flow of the application and includes all menus/screens from part B.
![StoryBoard_V3](/docs/img/StoryBoard_V3.png)

**Rubric Step E: Screenshots**
>Screenshots are provided for the APK under docs>SignedAPK.docx

**Rubric Step F: Readme File**
This file contains the following items:
1. Title and Purpose of the Application
2. Directions for operating the application and reaching all rubric aspects.
3. The signed APK version deployment.
4. A link to the git repository (Shown above).