# Licenser
jetpack compose license display lazy column ui

---

## Example
```kotlin
LazyColumn(
    modifier = Modifier
        .fillMaxSize()
        .padding(top = 8.dp),
    verticalArrangement = Arrangement.spacedBy(4.dp)
) {
    Licenser(
        listOf(
            Project("TEST", "https://sungbin.tistory.com/21", License.AGPL3),
            Project("TEST2", "https://sungbin.tistory.com/21", License.AGPL3),
            Project("TEST3", "https://sungbin.tistory.com/21", License.MIT),
            Project("TEST4", "https://sungbin.tistory.com/21", License.MIT),
            Project("TEST5", "https://sungbin.tistory.com/21", License.MIT),
            Project("TEST5", "https://sungbin.tistory.com/21", License.MIT),
            Project("TEST5", "https://sungbin.tistory.com/21", License.MIT),
            Project("TEST5", "https://sungbin.tistory.com/21", License.MIT),
            Project("TEST5", "https://sungbin.tistory.com/21", License.MIT),
            Project("TEST5", "https://sungbin.tistory.com/21", License.MIT),
            Project("TEST5", "https://sungbin.tistory.com/21", License.MIT),
            Project("TEST5", "https://sungbin.tistory.com/21", License.MIT),
            Project("TEST5", "https://sungbin.tistory.com/21", License.MIT),
            Project("TEST6", "https://sungbin.tistory.com/21", License.MIT),
            Project("TEST7", "https://sungbin.tistory.com/21", License.GPL3),
            Project("TEST7", "https://sungbin.tistory.com/21", License.GPL3),
            Project("TEST7", "https://sungbin.tistory.com/21", License.GPL3),
            Project("TEST7", "https://sungbin.tistory.com/21", License.GPL3),
            Project("TEST7", "https://sungbin.tistory.com/21", License.GPL3),
            Project("TEST7", "https://sungbin.tistory.com/21", License.GPL3),
            Project("TEST7", "https://sungbin.tistory.com/21", License.GPL3),
            Project("TEST7", "https://sungbin.tistory.com/21", License.GPL3),
            Project("TEST8", "https://sungbin.tistory.com/21", License.GPL3),
            Project("TEST9", "https://sungbin.tistory.com/21", License.BSD),
        )
    )
}
```
