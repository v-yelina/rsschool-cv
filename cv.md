## **Valiantsina Yelina**
-----

### **CONTACT INFORMATION**

* **Address:** Wendeschloßstrasse 49, 12559 Berlin, Germany
* **Phone:** +4915124447395
* **Email:** yelinavaliantsina@gmail.com
* **Github:** [v-yelina](https://github.com/v-yelina)
* **LinkedIn:** [Valiantsina Yelina](https://www.linkedin.com/in/valiantsina-yelina/)
* **Codewars:** [v-yelina](https://www.codewars.com/users/v-yelina)
-----

### **OBJECTIVE**
I’m seeking a job in an international company as a Junior Fullstack Developer to join the team and  produce high quality solutions for company customers. As a former software tester I am dedicated to constantly improving products. I am able to perform tasks myself but also want to learn from my colleagues and share my knowledge.

---

### **SKILLS**
**Front-End Stack:**  
HTML, CSS, JavaScript, React.js, Redux, Bootstrap


**Back-End Stack:**  
Node.js,  Express.js, Fastify, TypeScript, REST APIs, JSON


**Data:**  
MySQL, MongoDB


**Testing:**  
Postman, Jest, Mocha


**Development:**  
GIT, Docker, Agile, Scrum, Jira

---

### **CODE EXAMPLE**

```
<!-- You are given a dictionary/hash/object containing some languages and your test results in the given languages. Return the list of languages where your test score is at least 60, in descending order of the results. -->

function myLanguages(results) {
  let array = Object.entries(results).filter(([key, value]) => value >= 60).sort(([,a], [,b]) => (b - a));
  let output = [];
  array.forEach(([key, value]) => output.push(key));
  return output;
}
```