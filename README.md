# MyCore
<h1>Summary</h1>
  Two layered(UI-API)  End-to-end request process manager website created with .NET CORE ,using SQL for the database.

</br><h1>LOGIN</h1></br>
Used combined Windows&Basic authentication for system login.</br>
Two types of users using website : </br>
  -clients that request data,reports or specialized screens</br>
  -Admins that answer those request</br>
<h1>MAIN</h1></br>
 <p> For admins after login system welcomes you with main page that includes your performance graph that shows your completed requests rate for every request type compared to total requests received,
the requests that you are currently responsible of , the requests that waiting for someone to take responsibility and your notifications(message,changes in your requests,request appointment etc.)
For users you see the current status of your requests,the history of your completed requests and notifications.</p>
<h1>REQUEST LISTING</h1></br>
 <p>  A page with filters that you can use to search&find a specific request or list every request that fits your description</br>
also implemented quickfilters using javascript so basically you post a complex filter than filter that list using quickfilters if needed.</br></p>
<h1>REQUEST CREATING</h1></br>
  A page for clients to create requests.Other than textboxes page also has drag&drop area for file uploading , dynamic dropdown-lists to select request type and category or any report that currently active if needed.</br>
<h1>REQUEST MANAGEMENT</h1></br>
  A page for both clients-admins to use manage the process,Includes partial view live chat created with SSE(Server Send Events) logic so the workload of the server is minimized for a live chat.</br>
The things admins can do on the page:</br>
  Edit,take responsilibility ,cancel or complete request.</br>
  Chat with clients. </br>
  Save notes.</br>
The things clients can do on the page:</br>
  Edit or cancel request.</br>
  Chat with person responsible with the request. </br>
<h2>Perks</h2>
The entire system doesn't need any other comm enviroment or file share to solve the requests. </br>
Almost completely dynamic for the potential changes in the format can be customized by the changes in database no need to alter codes</br>
Minimized raw sql usage, no run-around codes,no exploration with url changes(form management)</br>
High Performance :Partial views,async functions ,no js time intervals(except voking SSE for chat) and summarized listings 
<h2>Disadvantages</h2>
Direct load of the shared Files:</br>
Request Management Page loads with file uploaded to the system related to the request so the user can download it.For cases download is not neccessary or already done can be marked as no need to load file data unless requested.(Currently working on it)</br>
HTML-CSS(responsibility and design):</br>
Tested only for the currently active users screens at the firm no problems at there but i am not happy with the looks at the wide-screen and bad returns for pick of color</br>

<h1>ADMIN MAIN PAGE</h1>


<img src='https://github.com/AyberkErdem/MyCore/assets/62530992/65546ce0-5852-4404-b30b-624267f2056a'/>
<h1>DESIGN</h1>

<img src='https://github.com/AyberkErdem/MyCore/assets/62530992/eeb00eef-27cd-4fbf-8c1c-98462e2a5ca1'/>

<h1>CREATING REQUEST</h1>

<img src='https://github.com/AyberkErdem/MyCore/assets/62530992/4b8cf167-7d99-449d-be69-352e9d4791a8'/>

<h1>REQUEST MANAGEMENT PAGE(CLIENT)</h1>
<p>Live chat created with SSE(server send events) adapted to .NET CORE </p>


<img src='https://github.com/AyberkErdem/MyCore/assets/62530992/4c319ff2-18f8-4707-accc-94536eead8bc'/>

<h1>REQUEST MANAGEMENT PAGE(ADMIN)</h1>

<img src='https://github.com/AyberkErdem/MyCore/assets/62530992/7e8a1990-56a1-45a0-a07a-d9b1f74fe182'/>

<h1>REQUEST LISTING</h1>

<p>Quick filters on the top filtering list using javascript without post/get actions</p>
<img src='https://github.com/AyberkErdem/MyCore/assets/62530992/6c69aba5-aaa2-4b4c-a75b-80488471bb7e'/>

<h1>DETAILED POST ACTION FILTER</h1>


<img src='https://github.com/AyberkErdem/MyCore/assets/62530992/31549eb6-1f1f-482b-9c2f-37b0472be363'/>
