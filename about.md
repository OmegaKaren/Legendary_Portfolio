--- 
layout: default
title: About Me
---
<html>
<div class="w3-content" style="max-width:1100px">
    <div class="w3-row w3-padding-64">
        <div class="w3-col m6 w3-padding-large">
            <p class="text-color"> Hi, I'm Gabriel Mulero, a multi-disciplined computer science student, particularly focused on python, sql, C++, and front end web development.   My goal is to use this website to showcase my skillsets to anyone  who is interested and document my learning journey to help others who are interesting in pursuing a career in software engineering. </p>
            <p class="text-color"> I am a 24 year old military veteran with five years of network engineering experience. I am a full-time student who currently lives in Fort Worth, Texas. I am currently looking for internships while I finish up my college degree to get hands on professional exprierence.</p>
        </div>  
        <div class="w3-col m6 w3-padding-large w3-hide-small">
            <img src="assets\images\1603833561597.jpg" class="w3-round w3-image w3-opacity-min">
        </div>             
    </div>
<div class="w3-container">
  <h2>Tabs in a Grid</h2>

  <div class="w3-row text-color">
    <a href="javascript:void(0)" onclick="showSkillz(event, 'Experience');">
      <div class="w3-third tablink w3-bottombar w3-hover-light-grey w3-padding text-color">Experience</div>
    </a>
    <a href="javascript:void(0)" onclick="showSkillz(event, 'ToolsandTechnology');">
      <div class="w3-third tablink w3-bottombar w3-hover-light-grey w3-padding text-color">Tools and Technology</div>
    </a>
    <a href="javascript:void(0)" onclick="showSkillz(event, 'skills');">
      <div class="w3-third tablink w3-bottombar w3-hover-light-grey w3-padding text-color">Skills</div>
    </a>
  </div>

  <div id="Experience" class="w3-container skills text-color w3-animate-bottom" style="display:none">
    <h2 class="w3-center">Experience</h2>
    <ul>
        <li class="w3-padding"><b>Full Time Student</b><br>Computer Science<br>Expected Graduation June 2023</li>
        <li class="w3-padding"><b>TekSystems</b><br>Network Specialist<br>August 2021 - May 2022</li>
        <li class="w3-padding"><b>Apex Technology</b><br>VIP Helpdesk Support<br>March 2021 - August 2021</li>
        <li class="w3-padding"><b>TekSystems</b><br>IT Support<br>January 2020 - March 2021 </li>
    </ul>    
  </div>

  <div id="ToolsandTechnology" class="w3-container skills text-color w3-animate-bottom" style="display:none">
    <h2 class="w3-center">Tools and Skills</h2>
    <ul>
        <li class="w3-padding"><b>Python</b></li>
        <li class="w3-padding"><b>SQL</b></li>
        <li class="w3-padding"><b>C++</b></li>
        <li class="w3-padding"><b>JavaScript</b></li>
        <li class="w3-padding"><b>HTML</b></li>
        <li class="w3-padding"><b>CSS/SASS</b></li>
        <li class="w3-padding"><b>Git</b></li>
        <li class="w3-padding"><b>Linux</b></li>
        <li class="w3-padding"><b>Visual Studio Code</b></li>
        <li class="w3-padding"><b>Postman</b></li>
    </ul>     
  </div>

  <div id="skills" class="w3-container skills text-color w3-animate-bottom" style="display:none">
    <h2 class="w3-center">Skills</h2>
    <ul>
        <li class="w3-padding"><b>Computer Programming and Coding</b></li>
        <li class="w3-padding"><b>Object-Oriented Design</b></li>
        <li class="w3-padding"><b>Software Testing and Debugging</b></li>
        <li class="w3-padding"><b>Problem Solving and Logical Thinking</b></li>
        <li class="w3-padding"><b>Superb Written and Verbal Communication</b></li>
        <li class="w3-padding"><b>TeamWork</b></li>
    </ul>    
  </div>
</div>

<script>
function showSkillz(evt, Portfolio) {
  var i, x, tablinks;
  x = document.getElementsByClassName("skills");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" w3-border-white", "");
  }
  document.getElementById(Portfolio).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-border-white";
}
</script>

</div>          
</div>
</html>