# Cyst 🥚

**Cyst** is a helper to ease the use of the JavaScript `localStorage` object of the browser

- on GitLab: [https://gitlab.com/k33g/cyst](https://gitlab.com/k33g/cyst)
- on GitHub: [https://github.com/k33g/cyst](https://github.com/k33g/cyst)

## Usage

```javascript
cyst.setItem("german_salutation", "Morgen")
cyst.setItem("english_salutation", "Hello")
v.setItem("french_salutation", "Salut")

cyst.items.filter(item => item[0].includes("salutation")) // 3 records
cyst.items.find(item => item[0].includes("salutation")) // 1 record ["german_salutation", "Morgen"]

cyst.items.forEach(item => console.log("key:", item[0], "value:", item[1]))
```

## TODO

- more examples

## Sandbox

> this part is only to test the bi-directional synchronisation
- 👋
- 🦊 15:26
- 🗿 15:37



