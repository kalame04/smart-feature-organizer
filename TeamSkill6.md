# Team Skill 6 - Building The Right System #

## 1. Adding New Projects ##

## 1.1 Use Case Description ##


| Use Case Name |	Adding New Projects |
|:--------------|:--------------------|
| Actors | Company Employee |
| Description | A new project is added to the SOFCS |
| Preconditions | Web-site is up and running; web-site opens in any web-browser; employee is logged into the system. |
| Basic Flow | 1. Click the Projects tab on the SOFCS web-application. |
|  | 2. Click the "Create Project" button. |
|  | 3. User fills the required fields such as Project Name, Project description, etc. |
|  | 4. User clicks Add Project button. |
|  | 6. Web-site takes User to the updated Projects page with the message, "Project added to the list of Projects." |
| Alternative Flows |	A1: User submits incomplete Add Projects form |
|  | A2: User clicks cancel button |
| Post-Conditions | Projects list updated and is visible on the SOFCSs Projects Tab |

## 1.2 Basic Flow of Use Cases ##

1. Click the Projects tab on the SOFCS web-application.

2. Click the "Create Project" button.

3. User fills the required fields such as Project Name, Project description, etc.

4. User clicks Add Project button.

6. Web-site takes User to the updated Projects page with the message, "Project added to the list of Projects."

## 1.3 Alternative Flows ##

A1: User submits incomplete Add Projects form

A2: User clicks cancel button

## 1.4 Use Case Flow Scenarios ##

![http://i.imgur.com/2NpjTeo.jpg](http://i.imgur.com/2NpjTeo.jpg)

## 1.5 All Scenarios ##

| Scenario # | Originating Flow | Alternative Flow |
|:-----------|:-----------------|:-----------------|
| 1. | Basic Flow |  |
| 2. | Basic Flow | A1 |
| 3. | Basic Flow | A2 |
| 4. | Basic Flow | A1, A2 |

## 1.6 Variables Identified ##

| Step | Variable(s) | Options to be tested |
|:-----|:------------|:---------------------|
| 1 | Required Fields | Empty required field(s), all required fields filled|
| 2 | Click cancel button | Click cancel button |

## 1.7 Test Paths ##

| Step | Variable(s) | Value | Expected Result | Pass/Fail |
|:-----|:------------|:------|:----------------|:----------|
| 1 | Required Field(s) | Fields Filled | Web-application takes user to updated Projects page, with the message, "Project successfully added to the list of projects." | Pass |
|  |  | Fields left blank | Web-application shows a pop-up message, "Required fields cannot be left blank." | Pass |
| 2 | Cancel Button | Click button | Web-application shows a pop-up message, "Add project method aborted by user." User is redirected to the Projects tab. | Pass |

## 2. Add the features ##

## 2.1 Use Case Description ##

| Use Case Name |	Add Features |
|:--------------|:-------------|
| Actors | Company Customer/User |
| Description | Add the features into the system |
| Preconditions | Valid user |
| Basic Flow | 1. Click the button to add the features. |
|  | 2. System pops up to enter the features and their attributes. |
|  | 3. Click the submit button to add the features. |
| Alternative Flows | A1. After step 2, click the cancel button to cancel the addition |
| Post-Conditions | Feature is added into the list |

## 2.2 Basic Flow of Use Cases ##

1. Click the button to add the features.

2. System pops up to enter the features and their attributes.

3. Click the submit button to add the features.

## 2.3 Alternative Flows ##

A1: After step 2, click the cancel button to cancel the addition

## 2.4 Use Case Flow Scenarios ##

![http://i.imgur.com/x4LQ1YA.jpg](http://i.imgur.com/x4LQ1YA.jpg)

## 2.5 All Scenarios ##

| Scenario # | Originating Flow | Alternative Flow |
|:-----------|:-----------------|:-----------------|
| 1. | Basic Flow |  |
| 2. | Basic Flow | A1 |

## 2.6 Variables Identified ##

| Step | Variable(s) | Options to be tested |
|:-----|:------------|:---------------------|
| 1 | Features | Submitting a feature & it's attributes, clicking cancel to abort feature addition process |

## 2.7 Test Paths ##

| Step | Variable(s) | Value | Expected Result | Pass/Fail |
|:-----|:------------|:------|:----------------|:----------|
| 1 | Features | Submit feature | Web-site shows user updated feature table with a message, "New Feature Added." | Pass |
| 2 | Features | Click cancel | Website shows current feature table with no changes made | Pass |

## 3. Organize Features ##

## 3.1 Use Case Description ##

| Use Case Name |	Organize Features |
|:--------------|:------------------|
| Actors | Company Customers |
| Description | Organize the features from the different users. |
| Preconditions | Features are collected |
| Basic Flow | 1. Click the button to edit/delete features. |
|  | 2. System displays the features. |
|  | 3. Select the features. |
|  | 4. Click edit button to modify. |
|  | 5. Click the submit button |
| Alternative Flows | A1. After step 3, click delete button in order to delete the feature then continue with step 5 |
| Post-Conditions | Feature edited or deleted |

## 3.2 Basic Flow of Use Cases ##

1. Click the button to edit/delete features.

2. System displays the features.

3. Select the features.

4. Click edit button to modify.

5. Click the submit button.

## 3.3 Alternative Flows ##

A1. After step 3, click delete button in order to delete the feature then continue with step 5

## 3.4 Use Case Flow Scenarios ##

![http://i.imgur.com/x4LQ1YA.jpg](http://i.imgur.com/x4LQ1YA.jpg)

## 3.5 All Scenarios ##

| Scenario # | Originating Flow | Alternative Flow |
|:-----------|:-----------------|:-----------------|
| 1. | Basic Flow |  |
| 2. | Basic Flow | A1 |

## 3.6 Variables Identified ##

| Step | Variable(s) | Options to be tested |
|:-----|:------------|:---------------------|
| 1 | Features | Editing a feature & it's attributes, clicking delete to remove feature(s) |

## 3.7 Test Paths ##

| Step | Variable(s) | Value | Expected Result | Pass/Fail |
|:-----|:------------|:------|:----------------|:----------|
| 1 | Features | Edit feature | Web-site shows user updated feature table with a message, "Feature Updated." | Pass |
| 2 | Features | Click delete | Web-site shows user updated feature table with a message, "Feature Deleted." | Pass |

## 4. Polling Features ##

## 4.1 Use Case Description ##

| Use Case Name |	Polling Features |
|:--------------|:-----------------|
| Actors | Users |
| Description |Polling each features from the different users. |
| Preconditions | Features are collected |
| Basic Flow | 1. Click the button to poll features. |
|  | 2. System displays the features. |
|  | 3. Select the features.  |
|  | 4. Enter the number from 0 - 5. |
|  | 5. Click the submit button |
|  | 6. Displays Successfully given rating for the feature |
| Alternative Flows | A1. Number greater than 5 or negative number given in step 4, After 5, it displays invalid input|
| Post-Conditions | Feature given with rating|

## 4.2 Basic Flow of Use Cases ##

1. Click the button to poll features.

2. System displays the features.

3. Select the features with rating input text box.

4. Enter the rate from 0 to 5.

5. Click the submit button.

6. System displays Successfully given rating for the feature.

## 4.3 Alternative Flows ##

A1. After step 5, if invalid data is entered, System displays invalid input, failed to rate the feature
## 4.4 Use Case Flow Scenarios ##

![http://i.imgur.com/x4LQ1YA.jpg](http://i.imgur.com/x4LQ1YA.jpg)

## 4.5 All Scenarios ##

| Scenario # | Originating Flow | Alternative Flow |
|:-----------|:-----------------|:-----------------|
| 1. | Basic Flow |  |
| 2. | Basic Flow | A1 |

## 4.6 Variables Identified ##

| Step | Variable(s) | Options to be tested |
|:-----|:------------|:---------------------|
| 1 | Features | polling feature(s) |

## 4.7 Test Paths ##

| Step | Variable(s) | Value | Expected Result | Pass/Fail |
|:-----|:------------|:------|:----------------|:----------|
| 1 | FeatureRating | 0 | "Successfully updated the rating for the feature |  |
| 2 | FeatureRating | 5 |"Successfully updated the rating for the feature |  |
| 3 | FeatureRating | -1 |"Invalid input. Failed to update the rating for the feature |  |
| 3 | FeatureRating | 6 |"Invalid input. Failed to update the rating for the feature |  |

## 5. Finalize Features ##

## 5.1 Use Case Description ##

| Use Case Name |	Finalize Features |
|:--------------|:------------------|
| Actors | Users |
| Description |Print features to final document. |
| Preconditions | Features are polled |
| Basic Flow | 1. Verify that features are correct |
|  | 2. Click Print button |
|  | 3. Document is prepared by system and printed  |
| Alternative Flows | A1. User clicks "Save" button at step 2. Rather than printing the document, the system saves the file to the users machine |
| Post-Conditions | Final Document Printed |

## 5.2 Basic Flow of Use Cases ##

1. User Verifies that features are correct

2. User clicks "print" button

3. System prepares final document and prints

## 5.3 Alternative Flows ##

A1. User clicks "Save" rather than print on step 2 and the system saves the document to the user's machine.

## 5.4 Use Case Flow Scenarios ##

![http://i.imgur.com/x4LQ1YA.jpg](http://i.imgur.com/x4LQ1YA.jpg)

## 5.5 All Scenarios ##

| Scenario # | Originating Flow | Alternative Flow |
|:-----------|:-----------------|:-----------------|
| 1. | Basic Flow |  |
| 2. | Basic Flow | A1 |

## 5.6 Variables Identified ##

| Step | Variable(s) | Options to be tested |
|:-----|:------------|:---------------------|
| 1 | Print Button | Click print button |
| 2 | Save Button | Click save button |

## 5.7 Test Paths ##

| Step | Variable(s) | Value | Expected Result | Pass/Fail |
|:-----|:------------|:------|:----------------|:----------|
| 1 | Save button | 1 |"Feature list document successfully created!" | Pass  |
| 2 | Print Button | 1 |"Sending document to printer."| Pass |