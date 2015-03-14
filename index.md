---
title: kylev.github.io Maven
layout: default
---

This is my Maven repo, published via GitHub pages. You can browse the
[contents on GitHub](https://github.com/kylev/maven).

Use `http://kylev.github.io/maven` as the repository to access my artifacts.
In Gradle, it looks like this:

```groovy
repositories {
    maven {
        name "kylev.github.io"
        url "http://kylev.github.io/maven"
    }
}
```
