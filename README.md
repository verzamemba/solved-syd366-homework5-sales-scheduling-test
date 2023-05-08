Download Link: https://assignmentchef.com/product/solved-syd366-homework5-sales-scheduling-test
<br>
<strong>Case Study</strong>

ProTKD Tae Kwon Do first opened their doors in 2001 at what now serves as their current head office in Thornhill, Ontario with the original business plan of offering Tae Kwon Do classes to children.

Business is booming as parents recognize that their children require regular exercise routines.  ProTKD Tae Kwon Do was rebranded and ProTKD Martial Arts and Fitness last year.  ProTKD now offers classes across the Greater Toronto Area, utilizing space in both their owned facilities and community centers.  Classes are now offered for adults as well as children.

New families must first enroll with ProTKD as children cannot be added to a class unless the ProTKD is able to contact parents on an emergency basis.  Once enrolled, parents are able to register for classes and purchase items at the ProTKD store.

Your team leader has written the following scenario to capture some of ProTKD’s store requirements.

<table>

 <tbody>

  <tr>

   <td width="125">Use Case Name</td>

   <td colspan="3" width="498">Record store sale of t-shirts</td>

  </tr>

  <tr>

   <td width="125">Triggering Event</td>

   <td colspan="3" width="498">Parent would like to purchase ProTKD branded t-shirts</td>

  </tr>

  <tr>

   <td width="125">Brief Description</td>

   <td colspan="3" width="498">Allows the Store Manager to record a new sale of t-shirts.</td>

  </tr>

  <tr>

   <td width="125">Actors</td>

   <td colspan="3" width="498">Store Manager</td>

  </tr>

  <tr>

   <td width="125">Related Use Cases</td>

   <td colspan="3" width="498"> </td>

  </tr>

  <tr>

   <td width="125">Preconditions</td>

   <td colspan="3" width="498">Store Manager has opened the Main Menu.</td>

  </tr>

  <tr>

   <td width="125">Post Conditions</td>

   <td colspan="3" width="498">Sale is saved to the database and now can be added to the parent’s end of the month bill</td>

  </tr>

  <tr>

   <td width="125">Flow of activities</td>

   <td colspan="2" width="252">Actor</td>

   <td width="246">System</td>

  </tr>

  <tr>

   <td width="125"> </td>

   <td width="30">1.</td>

   <td width="222">Requests to record a sale</td>

   <td width="246">Retrieves list of parents and prompts for selection. </td>

  </tr>

  <tr>

   <td width="125"> </td>

   <td width="30">2.</td>

   <td width="222">Selects a parent</td>

   <td width="246">Display of item types.  Prompts for selection.  Creates Sale assigning a unique identifier and sale date.  Assigns current semester the sale</td>

  </tr>

  <tr>

   <td width="125"> </td>

   <td width="30">3.</td>

   <td width="222">Selects T-Shirts</td>

   <td width="246">Displays a list of t-shirts including price.  Prompts for selection</td>

  </tr>

  <tr>

   <td width="125"> </td>

   <td width="30">4.</td>

   <td width="222">Selects required t-shirt</td>

   <td width="246">Displays T-Shirt. Prompts for quantity sold</td>

  </tr>

  <tr>

   <td width="125"> </td>

   <td width="30">5.</td>

   <td width="222">Enters quantity sold</td>

   <td width="246">Creates sale detail. Calculates taxes and total amount of the sale.  Displays the t-shirts sold.</td>

  </tr>

  <tr>

   <td width="125"> </td>

   <td width="30">6.</td>

   <td width="222">Repeats the above 2 steps until all t-shirts selected</td>

   <td width="246">Calculates taxes and total amount of the sale.  Displays the t-shirts sold.  Displays the sale. Prompts for confirmation</td>

  </tr>

  <tr>

   <td width="125"> </td>

   <td width="30">7.</td>

   <td width="222">Confirms sale</td>

   <td width="246">Adds the sale transaction.</td>

  </tr>

  <tr>

   <td width="125">Exception Conditions</td>

   <td colspan="3" width="498">·         Store Manager chooses to cancel adding the sale</td>

  </tr>

 </tbody>

</table>




<strong><u>Question 1</u></strong><u> </u>

Create a class diagram that supports the scenario.

<strong><u>Question 2</u></strong><u> </u>

Complete Object Level Sequence diagrams to support the above scenario.

<strong><u>Question 3</u></strong><u> </u>

The above scenario assumes that t-shirts are one size fits all.  What would happen if ProTKD decided to stock t-shirts in different sizes?  Please describe in English how you change the current model to support the new requirements.

<strong><u>Question 4</u></strong><u> </u>

As well as licensed merchandising, the ProTKD store sells snacks including granola bars and water.  One of their suppliers has a recall on their granola bars because of bacterial contamination.  ProTKD must contact parents who may have purchased the affected product.  How ProTKD use your model to support this request?  Please describe, in English, any changes to your model that should be made to support this request.

<strong><u>Part 2: Scheduling</u></strong>

You participated in a scheduling activity as part of week 9.  Please use that activity as the case study for this part of the test.

<strong><u>Question 5</u></strong><u> – Class Diagram </u>

Your task is to create a class diagram to support the activity and the scenario described below.

<table>

 <tbody>

  <tr>

   <td width="125">Use Case Name</td>

   <td colspan="3" width="516">Query Scheduled Classes for a Professor</td>

  </tr>

  <tr>

   <td width="125">Triggering Event</td>

   <td colspan="3" width="516">Professor requests their schedule</td>

  </tr>

  <tr>

   <td width="125">Brief Description</td>

   <td colspan="3" width="516">Allows a professor to request their scheduled with assigned classes and room numbers.  The query must produce an online report displaying the professor’s assigned classes for a week.</td>

  </tr>

  <tr>

   <td width="125">Actors</td>

   <td colspan="3" width="516">Professor</td>

  </tr>

  <tr>

   <td width="125">Related Use Cases</td>

   <td colspan="3" width="516"> </td>

  </tr>

  <tr>

   <td width="125">Preconditions</td>

   <td colspan="3" width="516">Professor has opened the Employee Menu</td>

  </tr>

  <tr>

   <td width="125">Post Conditions</td>

   <td colspan="3" width="516">Online report is displayed to the professor.</td>

  </tr>

  <tr>

   <td width="125">Flow of activities</td>

   <td colspan="2" width="270">Actor</td>

   <td width="246">System</td>

  </tr>

  <tr>

   <td width="125"> </td>

   <td width="48">1.</td>

   <td width="222">Requests Schedule</td>

   <td width="246">Uses login information to retrieve a schedule for the professor </td>

  </tr>

  <tr>

   <td width="125">Exception Conditions</td>

   <td colspan="3" width="516">·         Professor chooses to cancel retrieving their schedule</td>

  </tr>

  <tr>

   <td width="125"></td>

   <td width="48"></td>

   <td width="222"></td>

   <td width="246"></td>

  </tr>

 </tbody>

</table>




<strong><u>Question 6</u></strong><u> – Sequence diagram</u>

Please complete an object level sequence diagram to support the above scenario.