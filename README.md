Link: <a href="https://mernfirst.luckytaorem.epizy.com/">Check it out here</a>
# Quiz-web-Application-Using-QuizApi
This web Application is created using QuizApi APIs to get data and display it to the user and based on the user interaction, the points is being allocated and later display it to the user.
<ul>
<li>There are some Quiz Categories that you can choose between, After selecting it.</li>
<li>The quiz process will begin.</li>
<li>All Questions will be MCQs</li>
<li>There are total 10 question where each question is of 15 seconds.</li>
<li>You will not be allow to go back to previous question and no deduction of points for wrong answer.</li>
</ul>
<ul>
<li>**Event Handling and API Calls:**</li>
  <ul>
    <li>The code sets up event listeners for buttons (nextbtn and startbtn) to control the flow of the quiz application.</li>
    <li>When the “Let’s Start Quiz-Ky” button (startbtn) is clicked, the hiderules function is triggered.</li>
    <li>The hiderules function fetches quiz questions from an API based on the selected category (default is JavaScript) and displays them in the .questions-container.</li>
  </ul>
  
<li>**Global Variables**:</li>
  <ul>
    <li>Several global variables (index, data, total, etc.) are used to manage the quiz state.</li>
    <li>For example, index keeps track of the current question index, and total accumulates the user’s score.</li>
  </ul>
  
<li>**Timer and Question Navigation**:</li>
  <ul>
    <li>The setTimer function sets an interval to update the timer display.</li>
    <li>The nextquestion function handles moving to the next question, updating the timer, and displaying the result when all questions are answered.</li>
  </ul>
  
<li>**Result Display**:</li>
  <ul>
    <li>Depending on the total score, different messages and images are displayed (e.g., sad face, thumbs up, party icon).</li>
  </ul>
  
<li>**HTML Structure**:</li>
  <ul>
    <li>The HTML structure includes a navigation bar for the quiz category.</li>
    <li>Dynamically generated question elements are added to the .questions-container.</li>
  </ul>
  
<li>**API Call**:</li>
<ul>
    <li>The getdata function fetches quiz questions from the specified API URL using fetch and handles the response.</li>
</ul>
</ul>

<h1>Output:</h1>
<h2 align="center">Start Page</h2>

![Screenshot (395)](https://github.com/LuckyTaorem/Quiz-web-Application-Using-QuizApi/assets/67669132/3db610e7-48ac-4ab8-8398-fa6c38abfd0e)

<h2 align="center">Selection Page</h2>

![Screenshot (396)](https://github.com/LuckyTaorem/Quiz-web-Application-Using-QuizApi/assets/67669132/1bdc9eb3-d346-4ee8-abba-831bc8714f87)

<h2 align="center">Quiz Page</h2>

![Screenshot (397)](https://github.com/LuckyTaorem/Quiz-web-Application-Using-QuizApi/assets/67669132/ce580a59-716f-449e-ab7a-ba838c2b7585)

<h2 align="center">Result Page</h2>

![Screenshot (398)](https://github.com/LuckyTaorem/Quiz-web-Application-Using-QuizApi/assets/67669132/ba2093e8-1b58-4613-a972-9dde104724e8)
