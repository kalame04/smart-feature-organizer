# Team Skill 3 #
## 1.0 Introduction ##

### 1.1 Purpose of Vision Document ###

This section acts as an overview of the entire document. It establishes the users and their needs, an overview of the product, features and attributes, and requirements (product and documentation).

This vision document serves as the primary means of communication between the stakeholders and the project team.

### 1.2 Product Overview ###

Smart Feature Organizer will be used to collect and organize the features of any product captured from the customer. This can help avoid miscommunication, minimize oversights, save time during documentation, and most of all, provide a way to make sure that all of the features that the customer needs have been captured and agreed upon by both parties.

## 2.0 User Description ##

To have a successful project, it is imperative that both users and stakeholders' needs be correctly and fully understood. An understanding of those needs leads to creating a product that satisfies users and stakeholders. This section provides a profile of the stakeholders and users involved in the project and the key problems that they perceive should be addressed by the proposed solution.

### 2.1 Key User Needs ###

The following user needs were compiled based on interviews and a requirements workshop conducted by the project team:

From the customer's perspective:
  * Collect Features from all stakeholders with attributes and priority
  * Provision to organize the features
  * Provision to preview the features
  * Provision to delete the features
  * Provision for prioritizing features
  * Provision to print the features in a document
  * Provision to vote for the features
  * User Interface
  * Capability to upload documents
  * System Reliability
  * Easy to Use
  * System Availability
  * Interface is appealing
  * Ability to change and adapt features in the future

From the Project Team's (developers) perspective:
  * Collect features from all the stakeholders with attributes and priority
  * Handling collected features
  * User Interface
  * Ability to change and adapt features in the future

## 3. Product Overview ##

### 3.1 Product Perspective ###

In a demanding world, meeting with a customer and getting the features of a new product from them can become a tedious job. There can be problems such as miscommunication, oversights of what is needed for the final product, or the customer can change their mind constantly as to what is required. Our solution is the Smart Online Feature Collaboration system. This system can be used during customer meetings to capture/retrieve the features, organize them, prioritize them and generate a document during the meeting itself. Now, both parties can agree upon the required features from a single document which has been generated from this system.

### 3.2 SOFCS Product Position Statement ###

| **For** | companies wanting to collaborate on a project |
|:--------|:----------------------------------------------|
| **Who** | want to obtain their customer's desired features |
| **SOFCS** | is a system built to easily obtain, prioritize and organize the features of a new product |
| **That** | can be used within a company or with their customers |
| **Unlike** | other products that are not featured online |
| **Our product** | is based online and helps companies easily understand the features of a desired product |

### 3.3 Summary of Capabilities ###

| **Customer Benefits** | **Supporting Features** |
|:----------------------|:------------------------|
| Can easily collaborate on a project | Online Access |
| Obtain ideas from customer/company | Brainstorming Tool |
| Learn how to prioritize and/or eliminate features | Polling System |
| Agree upon and finalize the final list of features | Feature Document |
| Revise or revisit previous projects | Project Database |

### 3.4 Assumptions and Dependencies ###
  * Stake holders know English
  * Stake holders have the hardware/software available to utilize the system
  * Stake holders know how to navigate and use the web applications
  * Both parties having internet connection to be able to edit/update the features
  * Both parties able to communicate using an analog phone or VOIP to discuss the changes that need to be made on the system
  * A development team to work on bugs or enhancements of the system

### 3.5 Cost and Pricing ###
Will be determined after the final product has been completed

## 4.0 Feature Attributes ##

| **Function** | **Status** | **Risk** | **Priority** | **Stability** | **Target Release** |
|:-------------|:-----------|:---------|:-------------|:--------------|:-------------------|
| Login Credentials | Approved | Low | Critical | High | V 1.0 |
| Online/Web Application | Approved | High | Critical | Mid | V 1.0 |
| Edit/Delete Features | Approved | High | Critical | High | V 1.0 |
| Feature Polling | Approved | Low | Important | High | V 1.0 |
| Finalize Features | Approved | Low | Critical | High | V 1.0 |
| Updates/Patches | Approved | Low | Critical | Low | V 1.0 |

## 5.0 System Features ##

**5.1 Login:**
All users will have to Log-in to the system in order to use it. The system can assign permissions with the help of the system administrator.

**5.2 Add & Features With Attributes:**
Company must be able to automatically create and edit feature forms for the customers to add features.

**5.3 Feature Polling:**
After the features have been collected, users will have the option to vote for the features in order to get the system to organize the features.

**5.4 Display Finalized Features:**
After the user prompts the system to finalize the features list, the features are displayed as organized in the polling step.

## 6. Use case ##

<a href='Hidden comment: 
http://i.imgur.com/OkU4VP8.jpg
'></a>


![http://i.imgur.com/IJmKmxo.jpg](http://i.imgur.com/IJmKmxo.jpg)

| **Use case ID**| SOFCS\_USE\_CASE\_001|
|:---------------|:---------------------|
| **Use case Name**| Validate User |
| **Actors**| User, Customer|
| **Description**| Validate the user or customer to login |
| **Pre-condition**| Open the link in any web browser |
| **Post-condition**| Based on the user and customer they will have different privileges |
| **Normal Flow** | 1. System pops up to enter user name and password 2. Enter the user name and password 3. Click the login button 4. Navigate to the next page |
| **Alternative flow** |  After step 3, if it is a valid user, it displays "Login failed"  |


| **Use case ID**| SOFCS\_USE\_CASE\_002|
|:---------------|:---------------------|
| **Use case Name**| Add the Features |
| **Actors**| User|
| **Description**| Add the features into the system |
| **Pre-condition**| Valid user |
| **Post-condition**| Feature is added into the list|
| **Normal Flow** | 1. Click the button to add the features 2. System pops up to enter the features and their attributes 3. Click the submit button to add the features |
| **Alternative flow** | 1. After step 2, click the cancel button to cancel the addition |


| **Use case ID**| SOFCS\_USE\_CASE\_003|
|:---------------|:---------------------|
| **Use case Name**| Collect Features |
| **Actors**| Customer |
| **Description**| Collect the features from the different users |
| **Pre-condition**| Posted problem statement to collect features from the users/stakeholders |
| **Post-condition**| Stake holders can log in and add their features |
| **Normal Flow** | 1. Click the button to start collecting features 2. System prompts to enter the problem definition 3. Click Submit 4. Disable the start collecting button 5. Enables the Add features button  |
| **Alternative flow** | In step 2, if nothing is entered, in step 3, it pops up a message to enter the problem definition |


| **Use case ID**| SOFCS\_USE\_CASE\_004|
|:---------------|:---------------------|
| **Use case Name**| Organize Features |
| **Actors**| Customer |
| **Description**| Organize the features from the different users |
| **Pre-condition**| Features are collected and polling are done |
| **Post-condition**| Organized features |
| **Normal Flow** | 1. Click the button to organize features 2. System displays the features 3. Move the features 4. Click Submit button  |
| **Alternative flow** | After step 3, click cancel button in order to cancel the changes|


| **Use case ID**| SOFCS\_USE\_CASE\_005|
|:---------------|:---------------------|
| **Use case Name**| Edit/Delete Features|
| **Actors**| Customer |
| **Description**| Modify the features |
| **Pre-condition**| Features are collected and polling are done |
| **Post-condition**| Feature got edited or deleted|
| **Normal Flow** | 1. Click the button to edit/delete features 2. System displays the features 3. Select the features 4. Click edit button to modify 5. Click the submit button |
| **Alternative flow** | After step 3, click delete button in order to delete the feature then continue with step 5 |


| **Use case ID**| SOFCS\_USE\_CASE\_006|
|:---------------|:---------------------|
| **Use case Name**| Polling |
| **Actors**| Customer, User |
| **Description**| Enable polling |
| **Pre-condition**| Features are collected |
| **Post-condition**| Polling button enabled for user to poll |
| **Normal Flow** | 1. If it is logged in as customer, click the button to enable polling |
| **Alternative flow** | If it is logged in as user, click the polling button, displays the features - user can select the features and click the submit button |


| **Use case ID**| SOFCS\_USE\_CASE\_007|
|:---------------|:---------------------|
| **Use case Name**| Finalize the Features |
| **Actors**| Customer|
| **Description**| If freeze the features for further change|
| **Pre-condition**| Features are collected & organized |
| **Post-condition**| Polling button enabled for user to poll|
| **Normal Flow** | 1. Click the button to finalize the features |
| **Alternative flow** | None |


| **Use case ID**| SOFCS\_USE\_CASE\_008|
|:---------------|:---------------------|
| **Use case Name**| Display the Features |
| **Actors**| Customer|
| **Description**| Display all of the features |
| **Pre-condition**| Features are collected |
| **Post-condition**| Display the list of features|
| **Normal Flow** | 1. Click the button to display the features |
| **Alternative flow** | None |

## 7.0 Other Product Requirements ##

**7.1 Applicable standards**

  * Should have valid license to SOFCS software.
  * Membership should be up to-date.

**7.2 Licensing security and installation**
> Set of terms and conditions should be read and agreed.

**7.3 System Requirements**
> Computer should be capable of accessing the internet.

**7.4 Performance Requirements**
  * Feature suggesting customers must have good idea of the product.
  * The internet speed should be fast.

## 8.0 Documentation Requirements ##

**8.1 User Manual**
> User has the necessary instruction to use the Smart Online Feature Collaboration System.

**8.2 Installation Guides , configuration and Readme files**
> Since the the SOFCS is an online system no installation guides are provided.

**8.3 Labeling and Packaging**
> All terms in the agreements should be accepted before the use is actually allowed to work with the system.

## 9. Glossary ##
SOFCS = Smart Online Feature Collaboration System

No additional technical terms are required for understanding this document or project