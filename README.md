# 👋 Hi, I'm Joy!

<p style="font-size: 1.2em; line-height: 1.5em;">I have more than 11+ years of experience and high level knowledge of both the frontend and backend of web development. I have created several SaaS applications and numerous other web apps and websites. I have even created a fully functional drag and drop website builder. I am familiar with most modern web technologies and frameworks like ReactJS, NextJS, GraphQL etc.</p>

<p style="font-size: 1.2em; line-height: 1.5em;">I have fair knowledge of design suites like Figma, XD, Photoshop etc that makes my web design work top notch and effective. I am full stack developer, but I love building frontend more.</p>

<p style="font-size: 1.2em; line-height: 1.5em;">I am adaptable, have a friendly personality and bring positivity to the team. I can manage large projects and teams.</p>

<h4>I am currently working on - </h4><ul><li> 💇 Hairscope - AI powered hair analysis.</li><li> 🤖 Skingenii - All about skincare.</li></ul>
<h3>Check out my <a href='https://joy.skylinemeridian.com/'>Portfolio</a> to know more.</h3>
<br>
<blockquote>
<h3>If you're interested in the work I do, or like to discuss any projects, get in touch with me on <a href='https://www.linkedin.com/in/jayanta-sarkar-web-app-developer/'>LinkedIn</a>.</h3>
</blockquote>
<br>

## 🔗 Functional Joy:

```javascript
const salt = "qwerty@12345";

function decrypt(encoded) {
    const key = new TextEncoder().encode(salt);
    const bytes = Uint8Array.from(atob(encoded), char =>
        char.charCodeAt(0)
    );

    for (let i = 0; i < bytes.length; i++) {
        bytes[i] ^= key[i % key.length];
    }

    return new TextDecoder().decode(bytes);
}

function joy() {
    const mindset = decrypt("EhgLBh0XNV5HQBRZFBYXHB0XJw==");
    const mode = decrypt("GRYLFgdUL18SUUFcHRMAAA==");

    const passions = [
        "AQUKFgEaNBFbXVpaBxYRGxsX",
        "BRIGGhoWLF5VSg==",
        "FRITFxgWMFxXXUA=",
        "EwIWGxocM0ISUUFcHRMMHBM="
    ].map(decrypt);

    passions.map(passion => explore(passion));

    learn();
    build();
    improve();

    const passionText = passions.length > 1
        ? passions.slice(0, -1).join(", ") +
          decrypt("URYLFlQ=") + passions.at(-1)
        : passions[0];

    return decrypt("OxgcUklZIRE=") +
        mode +
        decrypt("UQcEAQcQL19TR1EVEBUKBwBZ") +
        passionText +
        decrypt("URYLFlQ=") +
        decrypt("EhgLBh0XNV5HQBRZFBYXHB0XJw==") +
        ".";
}

function explore(topic) {
    console.log(
        decrypt("NA8VHhsLKV9VEw==") +
        topic +
        decrypt("X1lLUgYYIlNbRxRdHhsAUhAcNFRRR1FRXw==")
    );
}

function learn() {
    const lessons = [
        "IAIAAQAQL18SUkdGBBoVBh0WLkI=",
        "IxIWFxULI1kSQVFZFBkRHhEKM11L",
        "PRIEABpZJkNdXhRYGAQREx8cMw=="
    ].map(decrypt);

    for (const lesson of lessons) {
        console.log(decrypt("HRIEABpRaRHQtaYV") + lesson);
    }

    console.warn(
        decrypt("OhkKBRgcJFZXE0FFFRYRFxBXYGBHVkdBGBgLAVQUNV1GWkRZGBIBXA==")
    );
}

function build() {
    const stages = [
        "ODM gMw==".replace(" ", ""),
        "ISUqJjstGWF3",
        "JTI2Jg==",
        "NTInJzM=",
        "Ij8sIg=="
    ].map(decrypt);

    stages.forEach((stage, index) => {
        console.log(
            decrypt("EwIMHhBRaRFp") +
            (index + 1) +
            decrypt("LFeH9OZZ") +
            stage
        );
    });

    console.warn(
        decrypt("OANFBRsLK0ISXFoVHA5FHxUaKFhcVhoVNRIVHhsAKV9VE1VbCAAEC1o=")
    );
}

function improve() {
    let progress = 0;

    while (progress < 100) {
        progress += 25;
        console.log(
            decrypt("GBoVABsPJRkbE9az41c1ABseMlRBQA4V") +
            progress +
            decrypt("VA==")
        );
    }

    console.error(
        decrypt("IRIXFBEaNFhdXRRbHgNFFBsMLlUcE2ZQHRIEAR0XJxFGW1EVBAcBEwAcbg==")
    );
}

joy()
```

<h4> Instructions for non-dev: </h4>
Copy the code, open your browser’s Developer Console (press F12 → Console), paste it, and press Enter to see the result.
On Mac, press ⌘ + Option + J in Chrome to open the Console directly, then paste the code and press Return.
<!--
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jayanta-sarkar-web-app-developer/) 

## 🎏 Love working with them:

<h4> 🌐 Web Page Design </h4>

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) 
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) 
![SASS](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white) 
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white) 
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) 

<h4> 🚀 JavaScript Stack </h4>

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) 
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) 
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) 
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) 
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white) 
![Chart.js](https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white) 

<h4> 📝 WordPress CMS Development </h4>

![WordPress](https://img.shields.io/badge/WordPress-%23117AC9.svg?style=for-the-badge&logo=WordPress&logoColor=white) 
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) 
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white) 

<h4> 💾 Databases, APIs and Deployments </h4>

![MySQL](https://img.shields.io/badge/mysql-%2300000f.svg?style=for-the-badge&logo=mysql&logoColor=white) 
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white) 
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) 
![GraphQL](https://img.shields.io/badge/-GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white) 
![Apollo-GraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) 
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) 

<h4> ☁️ Clouds </h4>

![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) 
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) 
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) 
![Firebase](https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black) 
![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white) 

<h4> 🎨 Design Expertise </h4>

![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) 
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white) 
![Adobe XD](https://img.shields.io/badge/Adobe%20XD-470137?style=for-the-badge&logo=Adobe%20XD&logoColor=#FF61F6) 
![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white) 

<h4> 📱 Mobile Frameworks </h4>

![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=for-the-badge&logo=Capacitor&logoColor=white) 
![Cordova](https://img.shields.io/badge/Cordova-35434F?style=for-the-badge&logo=apache-cordova&logoColor=%23E8E8E8) 
![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Expo](https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37) 
![Ionic](https://img.shields.io/badge/Ionic-%233880FF.svg?style=for-the-badge&logo=Ionic&logoColor=white) 
![Firebase](https://img.shields.io/badge/firebase-ffca28?style=for-the-badge&logo=firebase&logoColor=black) 

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=jtas01&theme=default&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=jtas01&theme=default&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=jtas01&theme=default&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=jtas01&theme=radical&no-frame=false&no-bg=true&margin-w=4)
-->
<!-- ### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=jtas01&limit=5&theme=monokai&combine_all_yearly_contributions=true) -->


<!--
**jtas01/jtas01** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
