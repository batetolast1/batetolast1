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

> 🏆 465 Contributions in the Year 2020
 > 
> 📦 14.8 kB Used in Github's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 16 Public Repositories
 > 
> 🔑 12 Private Repositories 

**I'm an Early 🐤** 

```text
🌞 Morning    51 commits     █████░░░░░░░░░░░░░░░░░░░░   21.79% 
🌆 Daytime    121 commits    █████████████░░░░░░░░░░░░   51.71% 
🌃 Evening    62 commits     ██████░░░░░░░░░░░░░░░░░░░   26.5% 
🌙 Night      0 commits      ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

```
📅 **I'm Most Productive on Saturday** 

```text
Monday       23 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.83% 
Tuesday      28 commits     ███░░░░░░░░░░░░░░░░░░░░░░   11.97% 
Wednesday    38 commits     ████░░░░░░░░░░░░░░░░░░░░░   16.24% 
Thursday     14 commits     █░░░░░░░░░░░░░░░░░░░░░░░░   5.98% 
Friday       20 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.55% 
Saturday     74 commits     ████████░░░░░░░░░░░░░░░░░   31.62% 
Sunday       37 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.81%

```


📊 **This Week I Spent My Time On** 

```text
💬 Programming Languages: 
Java                     15 hrs 30 mins      ██████████████████████░░░   87.79% 
Other                    1 hr 7 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   6.35% 
SQL                      36 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   3.47% 
XML                      18 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   1.75% 
Properties               5 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.52%

```

**I Mostly Code in Java** 

```text
Java                     22 repos            █████████████████████░░░░   84.62% 
CSS                      2 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   7.69% 
HTML                     1 repo              █░░░░░░░░░░░░░░░░░░░░░░░░   3.85% 
JavaScript               1 repo              █░░░░░░░░░░░░░░░░░░░░░░░░   3.85%

```



<!--END_SECTION:waka-->

-------

#### 👨‍💻 Readme was created with some help from the community! ❤️

- [anmol098/waka-readme-stats](https://github.com/anmol098/waka-readme-stats)
- [badges/shields](https://github.com/badges/shields)
