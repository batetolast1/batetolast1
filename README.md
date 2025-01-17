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

> 🏆 78 Contributions in the Year 2021
 > 
> 📦 17.3 kB Used in Github's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 21 Public Repositories 
 > 
> 🔑 16 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    76 commits     ████░░░░░░░░░░░░░░░░░░░░░   18.05% 
🌆 Daytime    218 commits    █████████████░░░░░░░░░░░░   51.78% 
🌃 Evening    127 commits    ███████░░░░░░░░░░░░░░░░░░   30.17% 
🌙 Night      0 commits      ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

```
📅 **I'm Most Productive on Saturday** 

```text
Monday       40 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.5% 
Tuesday      58 commits     ███░░░░░░░░░░░░░░░░░░░░░░   13.78% 
Wednesday    71 commits     ████░░░░░░░░░░░░░░░░░░░░░   16.86% 
Thursday     37 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.79% 
Friday       42 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.98% 
Saturday     87 commits     █████░░░░░░░░░░░░░░░░░░░░   20.67% 
Sunday       86 commits     █████░░░░░░░░░░░░░░░░░░░░   20.43%

```


📊 **This Week I Spent My Time On** 

```text
💬 Programming Languages: 
No Activity Tracked This Week

```

**I Mostly Code in Java** 

```text
Java                     28 repos            ██████████████████████░░░   87.5% 
CSS                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   6.25% 
HTML                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.12% 
JavaScript               1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.12%

```



 Last Updated on 04/09/2021
<!--END_SECTION:waka-->

-------

#### 👨‍💻 Readme was created with some help from the community! ❤️

- [anmol098/waka-readme-stats](https://github.com/anmol098/waka-readme-stats)
- [badges/shields](https://github.com/badges/shields)
