[![Open Source Love](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red.svg)](https://es.wikipedia.org/wiki/C%C3%B3digo_abierto)
![GitHub followers](https://img.shields.io/github/followers/hectrhcc?label=Followers&style=social)
![GitHub stars](https://img.shields.io/github/stars/hectrhcc?label=Stars&style=social)
<a href="https://www.linkedin.com/in/h%C3%A9ctor-helenio-contreras-corvacho/" target="_blank">
  <img align="left" width="20px" src="https://simpleicons.now.sh/linkedin/495f7e" />
</a>
<a href="https://codepen.io/hectrhcc/" target="_blank">
  <img  align="left"  width="20px" src="https://simpleicons.now.sh/codepen/495f7e" />
</a>

```js

const frontendDeveloper = {
  name: 'Hector',
  specialty: 'Frontend',
  technologies: ['HTML5', 'CSS3', 'JavaScript', 'JQuery', 'Bootstrap', 'Saas','React'],
  projects: [],

  addProject(project) {
    this.projects.push(project);
  },

  introduce() {
    console.log(`Hi, my name is ${this.name} and I'm a frontend developer.`); 
  }
}

const blog = {
  name: 'Blog personal'
};

const landing = {
  name: 'Landing page'  
};

frontendDeveloper.addProject(blog);
frontendDeveloper.addProject(landing);

frontendDeveloper.introduce();
```
