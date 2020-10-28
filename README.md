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
![Spring](https://img.shields.io/badge/Spring-2.3.4-blue?logo=spring)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-2020.2.3-blue?logo=intellij-idea)
![MySQL](https://img.shields.io/badge/MySQL-8.0.22-blue?logo=mysql)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-blue?logo=javascript)
![Bootstrap](https://img.shields.io/badge/Bootstrap-v4.5.2-blue?logo=bootstrap)

-------

<!--START_SECTION:waka-->
![Profile Views](http://img.shields.io/badge/Profile%20Views-0-blue)

**🐱 My Github Data** 

> 🏆 412 Contributions in the Year 2020
 > 
> 📦 14.6 kB Used in Github's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 14 Public Repositories
 > 
> 🔑 11 Private Repositories 

**I'm an Early 🐤** 

```text
🌞 Morning    50 commits     █████░░░░░░░░░░░░░░░░░░░░   22.42% 
🌆 Daytime    111 commits    ████████████░░░░░░░░░░░░░   49.78% 
🌃 Evening    62 commits     ███████░░░░░░░░░░░░░░░░░░   27.8% 
🌙 Night      0 commits      ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

```
📅 **I'm Most Productive on Saturday** 

```text
Monday       23 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.31% 
Tuesday      28 commits     ███░░░░░░░░░░░░░░░░░░░░░░   12.56% 
Wednesday    39 commits     ████░░░░░░░░░░░░░░░░░░░░░   17.49% 
Thursday     12 commits     █░░░░░░░░░░░░░░░░░░░░░░░░   5.38% 
Friday       18 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   8.07% 
Saturday     68 commits     ███████░░░░░░░░░░░░░░░░░░   30.49% 
Sunday       35 commits     ████░░░░░░░░░░░░░░░░░░░░░   15.7%

```


📊 **This Week I Spent My Time On** 

```text
💬 Programming Languages: 
Other                    2 hrs 28 mins       ██████████████████████░░░   90.19% 
Java                     14 mins             ██░░░░░░░░░░░░░░░░░░░░░░░   8.65% 
XML                      1 min               ░░░░░░░░░░░░░░░░░░░░░░░░░   0.72% 
Properties               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.38% 
Git Config               0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.07%

```

**I Mostly Code in Java** 

```text
Java                     19 repos            ████████████████████░░░░░   82.61% 
CSS                      2 repos             ██░░░░░░░░░░░░░░░░░░░░░░░   8.7% 
HTML                     1 repo              █░░░░░░░░░░░░░░░░░░░░░░░░   4.35% 
JavaScript               1 repo              █░░░░░░░░░░░░░░░░░░░░░░░░   4.35%

```



<!--END_SECTION:waka-->

-------

#### 👨‍💻 Readme was created with some help from the community! ❤️

- [anmol098/waka-readme-stats](https://github.com/anmol098/waka-readme-stats)
- [badges/shields](https://github.com/badges/shields)
