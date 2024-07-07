# 👋 Welcome to Eugene's GitHub Wonderland!
![Figma](https://img.shields.io/badge/-Figma-F24E1E?style=flat&logo=figma&logoColor=white)
![Dart](https://img.shields.io/badge/-Dart-0175C2?style=flat&logo=dart&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=white)
![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat&logo=flutter&logoColor=white)
![Flutter Flow](https://img.shields.io/badge/-Flutter%20Flow-02569B?style=flat&logo=flutter&logoColor=white)
---
```dart
import 'package:portfolio/aboutme.dart';
import 'package:portfolio/contact.dart';
import 'package:portfolio/achievements.dart';
import 'package:portfolio/projects.dart';

class GitHubPortfolio {
  AboutMe aboutMe = AboutMe(
      name: "Eugene Ow Jia Jun",
      age: 24,
      
      school: ["Nanyang Technologocial University (2024-2028)","Singapore Polytechnic (2019-2022)"],
      course: "Electrical and Electronics Engineering with Second major in Business",
      
      skills: ["UI/UX design", "Mobile/Web app development", "Business management"],
      software: ["Figma", "Dart", "Python", "Javascript", "Flutter", "Flutter Flow"]);

  Contact contact = Contact(
      email: 'mailto: eugeneow23@gmail.com',
      instagram: 'https://www.instagram.com/_.eugeneow',
      linkedIn: 'https://www.linkedin.com/in/eugene-ow/');

  List<RecentAchievements> recentAchievements = [
    RecentAchievements(
      name: "Diploma with Merit in Electrical and Electronics Engineering",
      year: [2022],
      type: "Academic award",
      organization: "Singapore Polytechnic"),
  ];

  List<CurrentProject> currentProject = [
    CurrentProject(
      name: "Custom image recognition pipeline",
      type: "Mobile application", 
      description:"This mobile app improves off-site experiences for construction "
                  "workers with features like tracking lorry locations, "
                  "managing lorry allocations, and calculating salaries." 
    ), 
  ];
}
```

