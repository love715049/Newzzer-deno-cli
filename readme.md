# Installation

```bash
deno install --allow-net --allow-read --allow-write --allow-env -n newzzer https://github.com/love715049/Newzzer-deno-cli/raw/master/mod.ts
```

# Usage

Find news related to a specific keyword

```bash
newzzer -query=19
```

Find news in a valid category
The valid categories are: business, entertainment, general, health, science, sports, technology

```bash
newzzer -category=general
```


### Reference 

[Creating your first News CLI app using Deno](https://medium.com/javascript-in-plain-english/creating-your-first-news-cli-app-using-deno-e1470398c627)