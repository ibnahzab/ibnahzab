<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
</style>
<script>
let slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>

<div align="center">
    <h1><img src="https://readme-typing-svg.herokuapp.com?font=Jetbrains+mono&size=40&duration=3000&color=33FF33&center=true&vCenter=true&width=435&lines=Ashar's Github" alt="Typing SVG"/></h1>
    
</div>

<div align="center">
    <h2>🚀 About Me</h2>
    <p>I am a software developer, embedded system engineer, AI enthusiast and consultant. I have been working since 2013 both in
    IT and electronics industries.
    Right now I am building aiseeyou.tech and digiboy-industries in my free time. I am open to work.
    </p>
</div>

<div align="center">
<h2 align="center" class="section-heading">🌐 Connect with Me</h2>
<p>Find me on LinkedIn, connect and let's us message each other to discuss opportunities.</p>
<div align="center">
  <a href="https://www.linkedin.com/in/aviezab">
    <img src="https://img.shields.io/badge/LinkedIn: Ashar-BBBBB5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
<a href="https://github.com/ibnahzab/ibnahzab" target="_blank">
    <img src="https://img.shields.io/badge/View%20on%20GitHub-%230077B5.svg?&style=for-the-badge&logo=github&logoColor=white" alt="GitHub Skyline"/>
</a>
<!-- <img src="https://komarev.com/ghpvc/?username=ibnahzab&style=for-the-badge" alt="Profile views" /> -->
</div>

<div align="center">
  <h2>🚀 Github Commits and Projects Showcase</h2>
    <p>This section highlights Github commits and all notable projects I have done in the past or the projects I am currently working on.</p>
  <img src="https://raw.githubusercontent.com/ibnahzab/ibnahzab/output/github-contribution-grid-snake-dark.svg#gh-dark-mode-only" alt="GitHub Contribution Grid Snake Animation Dark Mode"/>
  <!-- <img src="https://raw.githubusercontent.com/ibnahzab/ibnahzab/output/github-contribution-grid-snake.svg#gh-light-mode-only" alt="GitHub Contribution Grid Snake Animation Light Mode"/> -->
</div>

</div>
  <h2>🎓 Speaker and Mentoring Moments</h2>
  <p>This section highlights my actions during speaking in public or mentoring students.</p>
    <div class="slideshow-container">
        <div class="mySlides fade">
            <img src="https://ik.imagekit.io/yc79ommka/github-profile/djp_speaker1.png" style="width:100%"/>
            <div class="text">Speaking for Directorate of General Tax of Republic Indonesia</div>
        </div>
        <div class="mySlides fade">
            <img src="https://ik.imagekit.io/yc79ommka/github-profile/djp_speaker2.png" style="width:100%">
            <div class="text">Assisting for Directorate of General Tax of Republic Indonesia</div>
        </div>
        <div class="mySlides fade">
            <img src="https://ik.imagekit.io/yc79ommka/github-profile/djp_speaker3.png" style="width:100%">
            <div class="text">After Speaking for Directorate of General Tax of Republic Indonesia</div>
        </div>
        <div class="mySlides fade">
            <img src="https://ik.imagekit.io/yc79ommka/github-profile/bssn.png" style="width:100%">
            <div class="text">Finishing Project Face Recognition at National Cyber and Crypto Agency</div>
        </div>        
    <a class="prev" onclick="plusSlides(-1)">❮</a>
    <a class="next" onclick="plusSlides(1)">❯</a>
</div>
<br>
    <div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span> 
    <span class="dot" onclick="currentSlide(2)"></span> 
    <span class="dot" onclick="currentSlide(3)"></span> 
    </div>
</div>

<h2 align="center" class="section-heading">💻 Programming Languages</h2>
<p> Programming languages are tools, and I am happy to learn more. These are my daily programming languages:</p>
<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/C-F7DF1E?style=for-the-badge&logo=C&logoColor=black" alt="C"/>
  <img src="https://img.shields.io/badge/Embedded C++-4EAA25?style=for-the-badge&logo=c++&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/PHP-4EAA25?style=for-the-badge&logo=php&logoColor=white" alt="PHP"/>


</div>
<h2 align="center" class="section-heading">☁️ Cloud Technologies</h2>
<p>Despite my strong background in Electronics Engineering, I am also stepped in to the world of Cloud technologies:</p>
<div align="center">
  <img src="https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure"/>
  <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="GCP"/>
  <img src="https://img.shields.io/badge/Ansible-623CE4?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins"/>
  <img src="https://img.shields.io/badge/Github Actions-D24939?style=for-the-badge&logo=github&logoColor=white" alt="Github"/>
</div>

<div align="center">
<h2 align="center" class="section-heading"> 💻 Github Stats</h2>
<p>This github account is new, I don't know why my old account (@aviezab) banned by Github despite using it to contribute to open source projects and private repos, however, I am glade to share it again.</p>
 <table align="center" width="100%" height="100%" >
    <tr>
       <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ibnahzab&theme=github_dark" alt="Ashar's GitHub Stats"/></td>   
       <td><img style="border: none;" src="https://github-readme-streak-stats.herokuapp.com/?user=ibnahzab&theme=merko" alt="Ashar's Contribution Streak"/></td>
    </tr>
 </table>

 <table align="center" width="100%" height="100%" >
    <tr>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ibnahzab&theme=github_dark" alt="Ashar's GitHub Stats"/></td>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=ibnahzab&theme=github_dark&utcOffset=10" alt="Ashar's GitHub Stats"/>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ibnahzab&theme=github_dark" alt="Ashar's GitHub Stats"/></td>
        <td><img style="border: none;" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ibnahzab&theme=github_dark" alt="Ashar's GitHub Stats"/></td>
    </tr>
 </table>
</div>