![Coder Sultan](https://yt3.googleusercontent.com/I-RIjUt9RC9M-1Vc1hnHTWwXsIbMQVjhx7IU1UrgGrO_T-flWmSI1ql41rwJHo_HkV6hmgn0Tg=s160-c-k-c0x00ffffff-no-rj)

## CS Demo Data

This package has some different types of demo data like "Student Data", "Team Members Data", and "Demo Post Content".

Developers can simply import those data and use it directly on their project.

## Installation

To install this package, you first need Node js. Then open terminal from your code editor and command bellow code

> To install on dependencies run this code - Recommended

```console

$ npm install cs-demo-data

```

> To install on devDependencies run this code

```console

$ npm install cs-demo-data -D

```

Installation done !

## Usage

There has 3types of demo data you any of them base on your project requirements.

### Student Demo Data:

This module data you can use to build any education board result app. Their has all nessesary students data with subject name, marks, and code.

```js
import { studentData } from "./data";

studentData.map((item) => {
  const studentName = item.Name;

  console.log(studentName);
});
```

### Team Members Demo Data:

Using this module you can build team member section. There has team members Name, Role / Skill, Photo, and Scial Links.

```js
import { teamMembers } from "./data";

teamMembers.map((item) => {
  const memberName = item.name;

  console.log(memberName);
});
```

### Post Demo Data:

This module data you can use to build any Blog archive, News section.

```js
import { demoPost } from "./data";

demoPost.map((item) => {
  const postTitle = item.title;

  console.log(postTitle);
});
```
