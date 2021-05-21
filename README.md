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
> 📦 17.4 kB Used in Github's Storage 
 > 
> 💼 Opted to Hire
 > 
> 📜 21 Public Repositories 
 > 
> 🔑 16 Private Repositories  
 > 
**I'm an Early 🐤** 

```text
🌞 Morning    105 commits    █████░░░░░░░░░░░░░░░░░░░░   19.7% 
🌆 Daytime    260 commits    ████████████░░░░░░░░░░░░░   48.78% 
🌃 Evening    168 commits    ████████░░░░░░░░░░░░░░░░░   31.52% 
🌙 Night      0 commits      ░░░░░░░░░░░░░░░░░░░░░░░░░   0.0%

```
📅 **I'm Most Productive on Saturday** 

```text
Monday       55 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.32% 
Tuesday      69 commits     ███░░░░░░░░░░░░░░░░░░░░░░   12.95% 
Wednesday    93 commits     ████░░░░░░░░░░░░░░░░░░░░░   17.45% 
Thursday     49 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   9.19% 
Friday       57 commits     ██░░░░░░░░░░░░░░░░░░░░░░░   10.69% 
Saturday     113 commits    █████░░░░░░░░░░░░░░░░░░░░   21.2% 
Sunday       97 commits     ████░░░░░░░░░░░░░░░░░░░░░   18.2%

```


📊 **This Week I Spent My Time On** 

```text
💬 Programming Languages: 
Java                     34 hrs 45 mins      ██████████████████████░░░   90.51% 
XML                      1 hr 57 mins        █░░░░░░░░░░░░░░░░░░░░░░░░   5.09% 
Markdown                 1 hr 18 mins        ░░░░░░░░░░░░░░░░░░░░░░░░░   3.4% 
Properties               13 mins             ░░░░░░░░░░░░░░░░░░░░░░░░░   0.61% 
Other                    8 mins              ░░░░░░░░░░░░░░░░░░░░░░░░░   0.36%

```

**I Mostly Code in Java** 

```text
Java                     28 repos            ██████████████████████░░░   87.5% 
CSS                      2 repos             █░░░░░░░░░░░░░░░░░░░░░░░░   6.25% 
HTML                     1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.12% 
JavaScript               1 repo              ░░░░░░░░░░░░░░░░░░░░░░░░░   3.12%

```



<!--END_SECTION:waka-->

-------

#### 👨‍💻 Readme was created with some help from the community! ❤️

- [anmol098/waka-readme-stats](https://github.com/anmol098/waka-readme-stats)
- [badges/shields](https://github.com/badges/shields)
