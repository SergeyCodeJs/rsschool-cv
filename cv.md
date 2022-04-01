## Sergey Stekh

## Frontent developer

## Contact information:

**Phone:** *+79199054867*

**Email:** *sergeysteh@gmail.com*

**Telegram:** *@SergSteh*

---

## Briefly About Myself:

I started my career as a frontend developer in 2019. I am very interested in developing various projects, learning new technologies and applying knowledge in practice.
Completed training at RS-School (RS 2019 Q3). 

After learning, I worked on various freelance projects, but my main passion was programming and creating a startup - a Polish language school. This project uses PHP as the backend, and React is responsible for the frontend. Now this school is working, and many people use the software solutions I wrote, which is very inspiring for new achievements.

For me, programming is not just a hobby, but also a lifestyle, a way to earn money, constant training and self-development. I want to achieve the maximum in this area, and become a truly professional developer.

---

## Skills:

- HTML5; 
- CSS3;
- Bootstrap;
- JavaScript;
- React, Redux;
- Computer science fundamentals;
- Communication Protocols;
- Git;
- Webpack basics, GULP;
- Basic PHP;
- Vs Code;
- Figma.

## Soft Skills: 

- Able to work effectively under supervision;
- Ability to read, understand and clarify (if needed) task requirements;
- Able to explain thoughts in English;
- Able to present results of work to teammates;
- Understands when advice is needed, able to involve other team members in case of problems;
- Able to plan work time (Self-management, Time-management).

---

## Code example: 

```
import React from "react"
import "./ModulesList.css"

export default function ModulesList({state, modules, setState}) {
  
  function changeModule(e, newModule) {
    e.preventDefault();
    setState((prevState) => {
        return {
            ...prevState,
            previousModule: prevState.currentModule,
            currentModule: newModule[0],
            currentModuleName: newModule[1],
            currentSubModule: "All questions",
            data: {
              ...prevState.data,
              currentQuestionId: null,
              isQuestionOpen: false,
              questionData: null,
              questionsToShow: 15
            },
            search: {
              ...prevState.search,
              isSearching: false,
              searchString: "",
              foundQuestions: null
            },
            showCategories: false,
            testState: {
              isShowingTest: false
            }
        }
    })
  }

  return (
    <>
    <h2 className="modules-wrapper">Topics:</h2>
    <div className="modules-list">
      {modules.map((module, idx, arr) => {
        const active = module[0] === state.currentModule;

        return <div key={idx} className={active ? "single-module active" : "single-module"} onClick={(e) => changeModule(e, module)}>{module[1]}</div>
      })}
    </div>
    </>
  )
}
```

---

## Experience

- [Polish language school (HTML, CSS, JS, React, PHP)](https://polaka.ru); [Language test example](https://polaka.ru/polaka-free/?render=test&lessonId=1); [Grammar test example](https://polaka.ru/polaka-free/?render=grammar&lessonId=2); [Drag&Drop Example](https://polaka.ru/polaka-free?render=spriazenie&lessonId=2); [Learning words example](https://polaka.ru/polaka-free?render=new_words&lessonId=3);

- [SongBird Game (HTML, CSS, React + Redux)](https://song-bird-portfolio.netlify.app/); [Source code](https://github.com/SergeyCodeJs/song-bird-portfolio);

- [Quiz for KiwiTaxi international service (HTML + CSS)](https://kiwitaxiquiz.netlify.app/); [Source code](https://github.com/SergeyCodeJs/kiwitaxiQuiz);
- [Expo Forum (HTML, CSS)](https://expoforum.netlify.app/);

---

## Education:

- **June 2019 - September 2019** - HTMLAcademy HTML and CSS course;

- **October 2019 - November 2019** - Codecademy: learn HTML; learn CSS; learn JavaScript; building interactive JavaScript sites.

- **September 2019 - April 2020** - Rolling scopes school (RS 2019 Q3);

- **February 2020 - April 2020** - Udemy, "React JS – from beginner to professional";

- **April 2020 - June 2020** - Udemy, "Practical JavaScript (advanced level)";

- **June 2020 - August 2020** - Udemy, "React + Redux – Professional development".



