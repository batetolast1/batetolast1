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

> 🏆 63 Contributions in the Year 2021
 > 
> 📦 17.3 kB Used in Github's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 19 Public Repositories 
 > 
> 🔑 17 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    52 commits     █████░░░░░░░░░░░░░░░░░░░░   21.4% 
🌆 Daytime    124 commits    ████████████░░░░░░░░░░░░░   51.03% 
🌃 Evening    67 commits     ███████░░░░░░░░░░░░░░░░░░   27.57% 
🌙 Night      0 commits      ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

```
📅 **I'm Most Productive on Saturday** 

```text
Monday       25 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.29% 
Tuesday      28 commits     ███░░░░░░░░░░░░░░░░░░░░░░   11.52% 
Wednesday    40 commits     ████░░░░░░░░░░░░░░░░░░░░░   16.46% 
Thursday     15 commits     █░░░░░░░░░░░░░░░░░░░░░░░░   6.17% 
Friday       22 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.05% 
Saturday     74 commits     ███████░░░░░░░░░░░░░░░░░░   30.45% 
Sunday       39 commits     ████░░░░░░░░░░░░░░░░░░░░░   16.05%

```


📊 **This Week I Spent My Time On** 

```text
💬 Programming Languages: 
Java                     21 hrs 44 mins      ███████████████████████░░   93.37% 
JavaScript               1 hr 13 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.27% 
Properties               12 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.92% 
XML                      6 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.44% 
SQL                      0 secs              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

```

**I Mostly Code in Java** 

```text
Java                     27 repos            █████████████████████░░░░   87.1% 
CSS                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   6.45% 
HTML                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.23% 
JavaScript               1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.23%

```



<!--END_SECTION:waka-->

-------

#### 👨‍💻 Readme was created with some help from the community! ❤️

- [anmol098/waka-readme-stats](https://github.com/anmol098/waka-readme-stats)
- [badges/shields](https://github.com/badges/shields)
