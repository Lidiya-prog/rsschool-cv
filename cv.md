# Lidiya Morshchinina

## Contacts

* **Adress:** Russia, Saint Petersburg
* **Phone:** +7-912-897-34-10
* **E-mail:** lmorshchinka@gmail.com
* **Github:** Lidiya-prog

## Personal

I’m currently working in [OOO "Special technology center"](https://www.stc-spb.ru/),  I'm Engineer of the 2nd category ( frontend developer).

https://www.stc-spb.ru/

## Hard skills

* HTML
* CSS (Framework Bootstrap, Preprocessor SCSS, BEM methodology)
* JavaScript (Fundamentals,Functional Programming, OOP, Asynchronous JavaScript, ES6+,DOM),JSON
* TypeScript
* VueJS
* Vuex
* Vue router 
* Graph QL
* Git
* Firebase
* Jira
* Confluence
* Webpack
* Figma
* Windows OS, Linux(Ubuntu)

## Code examples

```
export class Question {
  static create(question) {
    return fetch(
      "https://podcast-app-project-1165d-default-rtdb.firebaseio.com/questions.json",
      {
        method: "POST",
        body: JSON.stringify(question),
        headers: {
          "Content-Type": "application/json",
        },
      }
    )
      .then((response) => response.json())
      .then((response) => {
        question.id = response.name;
        return question;
      })
      .then(addToLocalStorage)
      .then(Question.renderList);
  }
}
```

## Education

* **University:** South Ural State University,
BACHELOR OF LAW, 2018
* **Courses:**
    - JavaScript/Front-end 2022Q1, present
    - Professional layout, HTML ACADEMY, 2022
    - Vue js 3, VLADILEN MININ, 2022
    - Frontend-developer, GEEKBRAINS, 2021
    - JavaScript, [LEARN.JAVASCRIPT.RU](https://learn.javascript.ru/), 2021, 2022





