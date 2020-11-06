### 👋 Hi there! I'm Bartosz and I'm glad you're here! 🥰

-------

#### 🖊 Let's start with short introduction!

```Java
package io.github.batetolast1.batetolast1.domain.entities;

import java.util.Map;
import java.util.stream.Collectors;

public class GitHubBio extends Bio {

    private final String profile;
    private final Map<String, String> bio;

    public GitHubBio() {
        this.bio = Map.of(
                "🔭 I’m currently working on", "developing first apps in Spring 🍃",
                "🌱 I’m currently learning", "Java, of course! 🤓",
                "💬 Ask me about", "something other than Java? Well, guitars 🎸, fantasy 📖, PC 💻 and mobile 📲",
                "📫 How to reach me:", "e-mails should go to 📩 batetolast1@gmail.com; you can also say 👋"
        );
        this.profile = "https://github.com/batetolast1";
    }

    public GitHubBio(String profile, Map<String, String> bio) {
        this.profile = profile;
        this.bio = bio;
    }

    @Override
    public String getBio() {
        return bio.keySet()
                .stream()
                .map(key -> "- " + key + " **" + bio.get(key) + "**")
                .collect(Collectors.joining(System.lineSeparator()));
    }

    public String getProfile() {
        return profile;
    }
}
```

-------

#### 🚀 Technologies I'm currently mastering

![Java](https://img.shields.io/badge/Java-15-blue?logo=java)
![Spring](https://img.shields.io/badge/Spring-5.3-blue?logo=spring)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-2020.2.3-blue?logo=intellij-idea)
![MySQL](https://img.shields.io/badge/MySQL-8.0.22-blue?logo=mysql)
![JavaScript](https://img.shields.io/badge/JavaScript-ES11-blue?logo=javascript)
![Bootstrap](https://img.shields.io/badge/Bootstrap-v4.5.2-blue?logo=bootstrap)

-------

<!--START_SECTION:waka-->
**🐱 My Github Data** 

> 🏆 445 Contributions in the Year 2020
 > 
> 📦 14.7 kB Used in Github's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 15 Public Repositories
 > 
> 🔑 15 Private Repositories 

**I'm an Early 🐤** 

```text
🌞 Morning    51 commits     █████░░░░░░░░░░░░░░░░░░░░   22.37% 
🌆 Daytime    115 commits    ████████████░░░░░░░░░░░░░   50.44% 
🌃 Evening    62 commits     ██████░░░░░░░░░░░░░░░░░░░   27.19% 
🌙 Night      0 commits      ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

```
📅 **I'm Most Productive on Saturday** 

```text
Monday       23 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.09% 
Tuesday      28 commits     ███░░░░░░░░░░░░░░░░░░░░░░   12.28% 
Wednesday    39 commits     ████░░░░░░░░░░░░░░░░░░░░░   17.11% 
Thursday     12 commits     █░░░░░░░░░░░░░░░░░░░░░░░░   5.26% 
Friday       20 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.77% 
Saturday     71 commits     ███████░░░░░░░░░░░░░░░░░░   31.14% 
Sunday       35 commits     ███░░░░░░░░░░░░░░░░░░░░░░   15.35%

```


📊 **This Week I Spent My Time On** 

```text
💬 Programming Languages: 
Other                    14 hrs 11 mins      ██████████████░░░░░░░░░░░   58.56% 
Java                     6 hrs 35 mins       ██████░░░░░░░░░░░░░░░░░░░   27.22% 
XML                      1 hr 12 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.0% 
Properties               1 hr 5 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   4.54% 
HTML                     45 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.15%

```

**I Mostly Code in Java** 

```text
Java                     23 repos            █████████████████████░░░░   85.19% 
CSS                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   7.41% 
HTML                     1 repo              █░░░░░░░░░░░░░░░░░░░░░░░░   3.7% 
JavaScript               1 repo              █░░░░░░░░░░░░░░░░░░░░░░░░   3.7%

```



<!--END_SECTION:waka-->

-------

#### 👨‍💻 Readme was created with some help from the community! ❤️

- [anmol098/waka-readme-stats](https://github.com/anmol098/waka-readme-stats)
- [badges/shields](https://github.com/badges/shields)
