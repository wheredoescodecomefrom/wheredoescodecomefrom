```js
import SoftwareDeveloper from 'thejoepage';

class Bio extends SoftwareDeveloper {
  name     = 'Joe Page';
  title    = 'Software Engineer';
  company  = 'Anywhere Remote | For Hire';
  location = 'Nevada';
  website  = 'thejoe.page';
}

class Skills extends SoftwareDeveloper {
  languages  = ['JavaScript', 'TypeScript', 'Python', 'C++', 'C#', 'Java'];
  databases  = ['MySQL', 'MongoDB', 'PostgreSQL'];
  frameworks = ['React', 'React Native', 'Angular', 'GraphQL', 'Django', 'Flask', 'CppCMS', '.NET Core', '.NET Framework 3.5-4.72'];
  prefferedLang = 'JavaScript';
}

class Projects extends SoftwareDeveloper {
  portfolio       = 'thejoepage';
  badPacmanRemake = 'pacman.thejoe.page/';
}
```
