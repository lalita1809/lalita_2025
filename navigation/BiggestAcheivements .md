---
layout: page
title: Biggest Accomplishments and Takeaways
description: A blog for ideas for CompSci, etc.
permalink: /Biggest Achievements/

---


{% include nav/lessons.html %}

<style>
    body {
        font-family: 'Poppins', sans-serif;
        margin: 0;
        padding: 0;
        background: linear-gradient(135deg, #00c6ff, #0072ff, #00bfff, #1e90ff); /* Gradient for ocean colors */
        color: #333;
        text-align: center;
        animation: backgroundAnimation 20s ease infinite;
    }

    @keyframes backgroundAnimation {
        0% { background-position: 0% 50%; }
        50% { background-position: 100% 50%; }
        100% { background-position: 0% 50%; }
    }

    h1, h2 {
        font-weight: 700;
        animation: fadeInDown 1.5s ease-out;
    }

    h1 {
        font-size: 3em;
        color: #005f73;
        text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.1);
        margin-top: 30px;
    }

    h2 {
        font-size: 2.2em;
        color: #ff8c00;
        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
        margin-top: 40px;
        animation: slideInLeft 1.5s ease;
    }

    p {
        font-size: 1.5em;
        max-width: 800px;
        margin: 20px auto;
        line-height: 1.6;
        animation: fadeIn 2s ease;
        color: #2d3436;
    }

    .emoji {
        font-size: 2em;
    }

    .highlight {
        color: #ff6347;
        font-weight: bold;
    }

    ul {
        font-size: 1.3em;
        text-align: left;
        max-width: 600px;
        margin: 20px auto;
        padding-left: 20px;
        animation: fadeIn 2.5s ease-in;
    }

    li {
        margin-bottom: 12px;
        animation: fadeInUp 1.5s ease;
        border-bottom: 1px solid #ddd;
        padding-bottom: 8px;
    }

    /* Advanced animations */
    @keyframes fadeInDown {
        0% { opacity: 0; transform: translateY(-40px); }
        100% { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeIn {
        0% { opacity: 0; }
        100% { opacity: 1; }
    }

    @keyframes slideInLeft {
        0% { opacity: 0; transform: translateX(-100px); }
        100% { opacity: 1; transform: translateX(0); }
    }

    @keyframes fadeInUp {
        0% { opacity: 0; transform: translateY(40px); }
        100% { opacity: 1; transform: translateY(0); }
    }
</style>

<h1>My Journey So Far</h1>
<p><em>My Biggest takeways In the Past 6 weeks</em></p>


<h2><span class="emoji">⭐</span> My Coding Achievements</h2>
<ul>
    <li><span class="highlight">First Time Coding:</span> For my first big coding accomplishment I did was making my home page, learning how to use HTML in my about page.</li>
    <li><span class="highlight">GitHub Playground:</span> a more thorough exploration of Python and JavaScript that will allow me to experiment and learn more dynamically.</li>
    <li><span class="highlight">Frontend Mastery:</span> Through experimenting, I learned new methods to build on prior knowledge and produce useful, real-world applications.</li>
</ul>

<h2>Major Checkpoints in CSP</h2>
<ul>
    <li><span class="highlight">Making a public page:</span> Using the steps I did first making a local host page, I had to made a public page so everyone can see my accomplishments. It took a really long time but coming into office hours and after school and working with my peers made this accomplishment very noteable.</li>
    <li><span class="highlight">About Page Creation:</span> This page helped showcase who I am as a person and it also taught me how to make utterances. </li>
    <li><span class="highlight">First Issue Created:</span> An invaluable experience that showed us how to use GitHub's issue tracking system to communicate our ideas and collaborate with others.</li>
</ul>

<h2><span class="emoji">🌱</span> Learnings Currently</h2>
<ul>
    <li><strong>Currently:</strong> Learning the basics of Python and Javascript through the team teaches we had this past week, and also learning basics of HTML through VScode </li>
    <li><strong>Completed:</strong> Revisions for all assignments and compilation of lesson summaries onto the main webpage.</li>
</ul>

<h2>My Favorite Team Teach Accomplishments</h2>
<ul>
    <li><strong>3.1:</strong> Making the shopping list  and I decided to add something extra by adding the amount of quantity each item is and this way it can give a total score of the price you dont have to type in tooth brush twice you can just say 2 toothbrushes</li>
    <li><strong>3.2:</strong> I had issues with the language of code I was using. I decided to better my learning and change the code and the mistakes I did. I wanted to do this in order to take initiative and make sure I actually knew the content.</li>
    <li><strong>3.4:</strong> For 3.4 I was able to master concepts with manipulation of strings. My favorite hack was the palindrome convertor because I was able to use loops I leanred in perivious teachings to impliment into the knoweledge of strings.</li>
    <li><strong>3.6:</strong> My favorite part was  was to create a multiple choice test and I did a science test. I was able to combine my favorite interests such as space and science into a mc test and to learn about if else statements.</li>
    <li><strong>3.7:</strong> Covered fundamental web development (HTML, CSS). Upcoming topics include internet protocols and cybersecurity principles.</li>
<ul>

<h2> The main College Board Points that Stuck out to me </h2>
<ul>
    <li><strong>Global Impact:</strong> Recognizing privacy issues, the ethical and social effects of computing, and the wider societal ramifications.</li>
    <li><strong>Creative Development:</strong> utilizing technology to create innovative applications while emphasizing the value of innovation in computer science.</li>
    <li><strong>Exploring Computing Innovations:</strong> analyzed the impact of computing advancements on society and the advancement of technology through study.</li>
</ul>

<details>
   
    <pre>
        <code>
            <style>
                body {
                    font-family: 'Poppins', sans-serif;
                    margin: 0;
                    padding: 0;
                    text-align: center;
                    overflow: hidden; /* Prevents scrollbars */
                    background: linear-gradient(135deg, #00c6ff, #0072ff, #00bfff, #1e90ff); /* Gradient with ocean colors */
                    animation: gradient 15s ease infinite; /* Animate the background */
                }

                @keyframes gradient {
                    0% { background: #00c6ff; } /* Starting color */
                    25% { background: #0072ff; } /* Second color */
                    50% { background: #00bfff; } /* Third color */
                    75% { background: #1e90ff; } /* Fourth color */
                    100% { background: #00c6ff; } /* Ending color */
                }

                /* Submenu styling */
                .submenu {
                    color: black; /* Set text color to black */
                    background-color: rgba(255, 255, 255, 0.8); /* Optional: Add a background to increase contrast */
                    padding: 10px; /* Optional: Add padding */
                    border-radius: 5px; /* Optional: Round the corners */
                    display: none; /* Hide the submenu initially */
                }

                .submenu a {
                    color: black; /* Ensure links in submenu are also black */
                    text-decoration: none; /* Optional: Remove underline from links */
                }

                .submenu a:hover {
                    text-decoration: underline; /* Optional: Underline on hover */
                }
            </style>
        </code>
    </pre>
</details>

<style>
   body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #00c6ff, #0072ff, #00bfff, #1e90ff); /* Gradient for ocean colors */
    color: #333;
    text-align: center;
    animation: backgroundAnimation 20s ease infinite;
    overflow: auto; /* Allows scrolling */
}

    h1 {
        font-size: 3em;
        color: #005f73;
        margin-top: 20px;
        animation: fadeInDown 1s ease-in;
        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
    }

    h2 {
        font-size: 2.5em;
        color: #ff8c00;
        margin-top: 40px;
        animation: slideInLeft 1s ease-in;
        text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.1);
    }

    p {
        font-size: 1.5em;
        color: #333;
        max-width: 800px;
        margin: 20px auto;
        line-height: 1.6;
        animation: fadeIn 2s ease;
    }

    .emoji {
        font-size: 2em;
    }

    .highlight {
        color: #ff6347;
        font-weight: bold;
    }

    ul {
        font-size: 1.2em;
        text-align: left;
        max-width: 600px;
        margin: 20px auto;
        padding-left: 20px;
    }

    li {
        margin-bottom: 10px;
    }

    /* Keyframes for animations */
    @keyframes fadeInDown {
        0% {
            opacity: 0;
            transform: translateY(-30px);
        }
        100% {
            opacity: 1;
            transform: translateY(0);
        }
    }

    @keyframes fadeIn {
        0% {
            opacity: 0;
        }
        100% {
            opacity: 1;
        }
    }

    @keyframes slideInLeft {
        0% {
            opacity: 0;
            transform: translateX(-100px);
        }
        100% {
            opacity: 1;
            transform: translateX(0);
        }
    }
</style>

<script src="https://utteranc.es/client.js"
        repo="lalita1809/lalita_2025"
        issue-term="title"
        label="utterances"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>