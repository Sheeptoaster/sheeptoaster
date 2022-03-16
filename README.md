### Hi there 👋

```javascript
import JakeWeber, { React, Express, Flask, PostgreSQL, SQLAlchemy } from 'software-engineer';
import { useState } from 'react'


const App = () => {
   const [openToWork, setOpenToWork] = useState(true)
   
   const handleHire = (e) => {
    e.preventDefault();
    setOpenToWork(false);
   }
   
   return (
   <div>
      <h2>About Me</h2>
      {openToWork && (
        <button type='submit' onClick={handleHire}>Hire Me!</button>
        )
      }
   </div>
  )
}

const hobbies = ['Escape Rooms', 'Spending time with family', 'Video Games', 'Anything cats']

const Bio = () => {
  return (
    <ul>
      {hobbies.map((hobby, i) => 
        return <li key={i}>{hobby}</li>
      )}
    </ul>
  )
}

```


<div align='center'>
  <a href="https://www.linkedin.com/in/jacob-weber-662a08153/">
      <img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" alt="Jake Weber LinkedIn Profile" height="30" width="30">
  </a>

  <a href="https://angel.co/u/jacob-weber-6">
      <img src="https://www.vectorlogo.zone/logos/angel/angel-icon.svg" alt="Jake Weber AngelList Profile" height="30" width="30">
  </a>
  
  <a href="https://jakeweber.dev">
      <img src="https://cdn-icons-png.flaticon.com/512/351/351456.png" alt="Jake Weber Portfolio" height="30" width="30">
  </a>
</div>


<h2 align="center">Github stats :bar_chart:</h2>


<h3 align="center">Top Languages</h3>

<p align="center"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sheeptoaster&langs_count=10&theme=tokyonight&layout=compact" alt="GitHub Top Languages" /></p>

<h3 align="center">Profile stats :musical_keyboard:</h3>

<p align="center"><img src="https://github-readme-stats.vercel.app/api?username=sheeptoaster" alt="GitHub Stats" /></p>


