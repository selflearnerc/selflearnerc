<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Selflearnerc – AI Voice Intro</title>
</head>
<body style="background-color:#0D1117; color:white; font-family: Fira Code; text-align: center;">

  <!-- 🎯 TYPING ANIMATION -->
  <p>
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=007ACC&center=true&vCenter=true&width=800&lines=👋+Hi+there%2C+I'm+Selflearnerc!;🧠+Self-Learning+AI+%26+Python+Every+Day;🎯+Future+Goal:+Work+at+Google+or+OpenAI;💬+Learning+with+ChatGPT's+Help" alt="Typing Animation" />
  </p>

  <!-- 🌊 MODERN BANNER -->
  <p>
    <img src="https://capsule-render.vercel.app/api?type=waving&color=0D1117&height=200&section=header&text=Welcome%20to%20My%20AI%20World!&fontSize=36&fontColor=ffffff&animation=fadeIn" />
  </p>

  <!-- 🔊 AI VOICE SCRIPT -->
  <script>
    window.onload = function () {
      const textLines = [
        "Hi there, I'm Selflearnerc!",
        "Self-Learning AI and Python Every Day.",
        "Future Goal: Work at Google or OpenAI.",
        "Learning with ChatGPT's Help."
      ];

      let index = 0;

      function speakNextLine() {
        if (index < textLines.length) {
          const utterance = new SpeechSynthesisUtterance(textLines[index]);
          utterance.lang = "en-US";
          utterance.rate = 1;
          utterance.pitch = 1;
          speechSynthesis.speak(utterance);
          index++;
          setTimeout(speakNextLine, 3000); // wait 3 seconds before next line
        }
      }

      speakNextLine();
    };
  </script>

</body>
</html>




### 🧠 About Me:
-  I'm a passionate self-learner on a journey to become an AI/ML expert
-  I learn daily with the help of **ChatGPT** – my virtual coding buddy
-  recently built a **Python calculator** (my first hands-on project!)
-  Learning Python from scratch – one day, one concept at a time
-  I believe in consistent practice and building projects to grow
-  **Future Goal:** I dream of working at top companies like **Google**, **OpenAI**, or **DeepMind**

---

### 📅 My Learning Plan:
-  Master Python basics and logic building
-  Learn foundational topics in Machine Learning
-  Build real-world mini projects (e.g., calculator, to-do app, chatbot)
-  Explore data science tools like Pandas,Tensorflow, NumPy (soon!)
-  Build a strong portfolio to apply for internships and jobs

---

### 🧰 Tools Helping Me Learn:
-  ChatGPT (daily help, doubt solving, explanations)
-  YouTube tutorials (e.g., codewithharry, freecodecamp)
-  W3Schools, GeeksforGeeks, and official docs

---

### 🤝 Let's Connect:
> If you're also a self-learner, feel free to collaborate or connect!


