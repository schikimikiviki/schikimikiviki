# viktoriabzdyk.java

---

```
package com.developer-portfolio.backend.service.runner;

@Configuration
public class UserLoaderConfig {

    @Bean
    CommandLineRunner run() {
        return args -> {

            addUserIfNotExists("Viki", 27, "https://vbdev.at", "Junior Developer", "next:urban",

                "JavaScript, Java, HTML, CSS, React, PHP, SQL", Set.of("ADMIN"));

        };
    }

}
```
