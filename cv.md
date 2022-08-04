## [Dzhyhota Anna](https://github.com/AnnaDzig)

![Anna's picture](https://pbs.twimg.com/profile_images/1187491455708880901/WZFHU0dp_200x200.jpg)
_A student of The Rolling Scopes School._

### Contacts:

- Ukraine, Mykolaiv/ Denmark, Kolding;
- Email Adress: adzyhota@protonmail.com;
- Phone: +380974811561/ +4526661259;
- Telegram/Viber: +380974811561;

### About Me

Creative and self-starting Front-End Developer with no experience but with a huge willing of building stable eCommerce websites and apps in fast-paced, collaborative environments. Skilled in HTML/CSS/JavaScript/ and knowledgeable of Figma. Passionate about learning new skills and technologies.

### Education

Petro Mohyla Black Sea National University,department of Sociology, Master's degree in Social work.

### Additional Education

Rolling Scopes School stage#0

### The code Example

_Navbar Effect_

```javascript
const fullImg = document.querySelector(".full-img");
const smallImg = document.querySelectorAll(".gallery img");
const modal = document.querySelector(".modal");

// console.log(smallImg);
smallImg.forEach(function (img) {
  img.addEventListener("click", function () {
    modal.classList.add("open");
    fullImg.classList.add("open");

    // Changin' the images dynamically
    const originalQuality = img.getAttribute("alt");
    fullImg.src = `img/full/${originalQuality}.jpg`;
  });
});

modal.addEventListener("click", function (e) {
  if (e.target.classList.contains("modal")) {
    modal.classList.remove("open");
    fullImg.classList.remove("open");
  }
});
```

### Additional education:

[Udemy Courses]

- [JavaScript Zero to Expert Complete 2021 Guide + 50 Projects](https://www.udemy.com/course/javascript-zero-to-expert-the-complete-modern-guide-build-real-apps)
- [The Complete 2021 Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp)

| **Skills** | **Level**    |
| ---------- | ------------ |
| HTML       | Intermediate |
| CSS        | Intermediate |
| GIT        | Intermediate |
| Javascript | Beginner     |
| Figma      | Intermediate |
| English    | Advanced     |
