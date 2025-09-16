# 👨‍💻🌐 Welcome to Eugene's GitHub Wonderland!
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
      age: 25,

      education: ["Nanyang Technologocial University (2024-2028)","Singapore Polytechnic (2019-2022)"],
      course: "Electrical and Electronics Engineering with Second major in Business",
      
      skills: ["UI/UX design", "Mobile/Web app development", "Business management"],
      software: ["Figma", "Dart", "Python", "Javascript", "Flutter", "Flutter Flow"]);

  Contact contact = Contact(
      email: 'eugeneow23@gmail.com',
      instagram: 'https://www.instagram.com/_.eugeneow',
      linkedIn: 'https://www.linkedin.com/in/eugene-ow/');

  List<RecentAchievements> recentAchievements = [
    
    RecentAchievements(
      name: "Undergraduate Research Experience On Campus (URECA)",
      year: [2024],
      type: "Research Programme",
      organization: "Nanyang Technological University"),

    RecentAchievements(
      name: "Diploma with Merit in Electrical and Electronics Engineering",
      year: [2022],
      type: "Academic award",
      organization: "Singapore Polytechnic"),
  ];

  List<CurrentProject> currentProject = [
    CurrentProject(
      name: "TailGNN",
      type: "Research Programme", 
      content: "This project aims to build a dynamic, graph-based model for forecasting tail 
            risk and systemic contagion in the U.S. equity market, mainly focusing on the individual constituents 
            of the S&P 500 (SPY) index. We will attempt this by using both a Small Feedforward Neural Network 
            followed by a Temporal Graph Neural Nework (TGNN) with daily recorded, minute-level, Level 1 (L1) data."
    ), 
  ];
}
```

