# Hi! 👋

**_I am a skilled software developer specializing in React Native, backend services, and cloud infrastructure._**

[![LinkedIn](https://i.sstatic.net/gVE0j.png)](https://www.linkedin.com/in/mehmet-esad-kiris-566a60126/)

```js
const aboutMe = {
  greeting: "Hello, World! 👋 🌎",
  education: "📚 Alumnus of Florida Atlantic University 🦉",
  currentWork: "🔭 Currently focusing on Expo and CRUD app development",
  contact: "📫 Connect with me on LinkedIn",
  funFact: "⚡ Fun fact: Former professional basketball player, passionate about soccer ⚽",
  additionalSkills: [
    "Developing dashboards using FeatherJS",
    "Building applications with React Native and Expo",
    "Writing tests with Mocha and Chai",
    "Managing applications with PM2",
    "Implementing event-driven systems with NATS",
    "Automating tasks with Gulp",
    "Managing databases with SQL and PostgreSQL",
    "Proficient in AWS"
  ]
};

function displayAboutMe() {
  console.log(aboutMe.greeting);
  console.log(aboutMe.education);
  console.log(aboutMe.currentWork);
  console.log(aboutMe.contact);
  console.log(aboutMe.funFact);
  console.log("🛠️ Additional Skills:");
  aboutMe.additionalSkills.forEach(skill => console.log(`- ${skill}`));
}

displayAboutMe();
```
