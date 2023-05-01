Download Link: https://assignmentchef.com/product/solved-beartooth-hiking-company
<br>
Beartooth Hiking Company liked your initial design, but has a couple of requests. Is it possible to make sure the number of the people in the party is at least 1, but no more than 10? Also, they’d like to validate the date input somehow (Your choice, you can just verify the fields from the last <a href="https://www.justanswer.com/topics-homework/">homework</a>, or if you get brave, you could incorporate a JavaScript Date Picker object (see here, here or here for an example, but you can use your own if you want). In addition, they want to make sure that if you haven’t done so already, you should use JavaScript to ensure that only correct durations are offerred for each hike. They also want to make sure that the site doesn’t do anything like presenting an incorrect date to the user (like June 31st), so if you don’t use a Date Picker, use JavaScript to adjust the available dates for a month.(If you think about it, you don’t need to use JavaScript for the number in the party, there is a better way than validating raw text input). Remember, you need to use JavaScript in the project, and it needs to be used to validate or create input before it is sent to the server.You’ll want to put most of your JavaScript in their own files, otherwise you’ll have to write out the code from within the Servlet.

<p style="font-weight: 400;"> test case inputs:

<ol>

 <li>Gardiner Lake, 3 Days starting on 8/1/2021</li>

 <li>Gardiner Lake, 7 Days starting on 8/1/2021</li>

 <li>Beaten Path, 5 days starting on 10/1/2022</li>

 <li>Hellroaring Plateau, 7 days starting on 07/1/2031</li>

 <li>Hellroaring Plateau, 3 Days, starting on 10/t/2022  —- note that this is bad date input</li>

 <li>Gardiner Lake, X Days (bad input) starting on 8/15/2023 — bad input</li>

 <li>Beaten Path, 5 days starting on 8/1/2041  — should not work as valid years up to 2040</li>

 <li>Gardiner Lake, 3 Days starting on 7/1/2021 — even though helper classes will allow – you should not allow bookings in the past</li>

</ol>