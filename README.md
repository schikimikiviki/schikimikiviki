# viktoriabzdyk.java

---

```
package com.developer-portfolio.backend.service.runner;

@Configuration
public class UserLoaderConfig {

    @Bean
    CommandLineRunner run() {
        return args -> {

            addUserIfNotExists("Viki", 1997, "https://vbdev.at", "Fullstack Developer"

                "C, JavaScript, Java, HTML, CSS, React, PHP, SQL", Set.of("ADMIN"));

        };
    }

}
```
