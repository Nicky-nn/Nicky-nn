<h1 align="center">Hi <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Hi.gif" width="35" />, I'm Nick</h1>
<h3 align="center">I'm Nick Russell, a <span id="age"></span>-year-old Bolivian Independent FullStack Developer, a weird guy who likes to do weird things with technologies and related to design, developing experiences and web applications. When I'm not working or playing, I plan how to escape from the University.</h3>
- 👨‍💻 All of my projects are available at [https://nick-russell.vercel.app/](https://nick-russell.vercel.app/) <img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30">
- 💬 Ask me about **react, vue, angular**
- 📫 How to reach me **nick077n@gmail.com**
- 👯 We can connect to play some games ♟
- ⚡ Fun fact **Je connais un peu le français**
- 🧑‍💻 Tech I work on : 

<script>
  const birthDate = new Date('2002-02-26');
  const today = new Date();
  const age = today.getFullYear() - birthDate.getFullYear();
  const monthDiff = today.getMonth() - birthDate.getMonth();

  if (monthDiff < 0 || (monthDiff === 0 && today.getDate() < birthDate.getDate())) {
    document.getElementById('age').textContent = age - 1;
  } else {
    document.getElementById('age').textContent = age;
  }

  const currentYear = today.getFullYear();
  const startOfYear = new Date(currentYear, 0, 1);
  const dayOfYear = Math.floor((today - startOfYear) / (24 * 60 * 60 * 1000));
  const daysInYear = isLeapYear(currentYear) ? 366 : 365;
  const progressPercentage = (dayOfYear / daysInYear * 100).toFixed(2);

  const progressBar = '■'.repeat(Math.floor(progressPercentage / 4)) + '▢'.repeat(25 - Math.floor(progressPercentage / 4));

  document.getElementById('year-progress').innerHTML = `{ ${progressBar} } ${progressPercentage} %`;
  document.getElementById('current-date').textContent = today.toDateString();

  function isLeapYear(year) {
    return (year % 4 === 0 && year % 100 !== 0) || year % 400 === 0;
  }
</script>

<h3 align="left">Languages and Tools:</h3>
<p align="center"> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://flutter.dev" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/> </a> <a href="https://golang.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="go" width="40" height="40"/> </a> <a href="https://graphql.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/graphql/graphql-icon.svg" alt="graphql" width="40" height="40"/> </a> <a href="https://ionicframework.com" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/d/d1/Ionic_Logo.svg" alt="ionic" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://kotlinlang.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/kotlinlang/kotlinlang-icon.svg" alt="kotlin" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://reactnative.dev/" target="_blank" rel="noreferrer"> <img src="https://reactnative.dev/img/header_logo.svg" alt="reactnative" width="40" height="40"/> </a> <a href="https://sass-lang.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg" alt="sass" width="40" height="40"/> </a> <a href="https://developer.apple.com/swift/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/swift/swift-original.svg" alt="swift" width="40" height="40"/> </a> </p>


---
### <img src='https://media1.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif?cid=ecf05e47x2g034i9pzwtzzsd3xgg2w9nr94t4tflbbgo3008&rid=giphy.gif' width='25' /> My Github Stats:

![Nick's GitHub stats](https://github-readme-stats.vercel.app/api?username=nicky-nn&show_icons=true&title_color=ffc857&icon_color=8ac926&text_color=daf7dc&bg_color=151515&hide=issues&count)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=nicky-nn&layout=compact&text_color=daf7dc&bg_color=151515&hide=css,html,php)](https://github.com/anuraghazra/github-readme-stats)
[![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=nicky-nn&theme=dark)](https://git.io/streak-stats)

<!--START_SECTION:waka-->

<!--END_SECTION:waka-->

⏳ **Year Progress** <span id="year-progress"></span> as on <span id="current-date"></span>

---

<h3 align="left">Connect with me:</h3>
<p align="center">
<a href="https://dev.to/nickynn" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/devto.svg" alt="nickynn" height="30" width="40" /></a>
<a href="https://twitter.com/nick_russell_in" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="nick_russell_in" height="30" width="40" /></a>
<a href="https://linkedin.com/in/nickynn/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="nickynn/" height="30" width="40" /></a>
</p>
