### Hi there! 👋 I'm Bartosz and I'm glad you're here! 🥰

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

#### Technologies I'm currently mastering

![Java](https://img.shields.io/badge/Java-15-blue?logo=java)
![Spring](https://img.shields.io/badge/Spring-2.3.4-blue?logo=spring)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-2020.2.3-blue?logo=intellij-idea)
![MySQL](https://img.shields.io/badge/MySQL-8.0.22-blue?logo=mysql)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-blue?logo=javascript)
![Bootstrap](https://img.shields.io/badge/Bootstrap-v4.5.2-blue?logo=bootstrap)

-------
