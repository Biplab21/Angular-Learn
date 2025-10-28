# Day 01

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 20.1.4.

- Install Angular CLI

```bash
npm install -g @angular/cli
```

- Check Angular CLI version


```bash
ng version
```

- Create new project


```bash
ng new <project-name>
```

- Start a project


```bash
npm start
```

- In the **.ts** file for example in **app.ts** file we can create properties like this
Here we do not want to use any keywords like let, var and const

- To access this properties in the **.html** file we need to use **'interpolation'** which is denoted with **{{}}**. We need to put the property name inside **{{}}** like this


`<h1>&#123;&#123;title&#125;&#125;</h1>`

We can write JS code also inside **'interpolation'**

- We can generate a new component by using this below command

```bash
ng g c <component-name>
```

- We need to use the selector name which can be found inside the **.ts** file and we have to import that component
