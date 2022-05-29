
![logo.flatedit.com](https://logo.flatedit.com/1/cover.png)

# [examples.flatedit.com](https://examples.flatedit.com/) [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/flatedit/examples/edit/main/DOCS/MENU.md) 

+ [Kod źródłowy - examples.flatedit.com](http://examples.flatedit.com)
+ [Strona informacyjna: www.flatedit.com](https://www.flatedit.com/)
+ [Dokumentacja - docs.flatedit.com](https://docs.flatedit.com/)
+ [Logotyp: logo.flatedit.com](https://logo.flatedit.com/)

+ [LICENSE](LICENSE)



## About flatedit [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/flatedit/examples/edit/main/DOCS/ABOUT.md)

creating documentation is not easy in hundreds of small projects, where are dependencies
we need some simple tool to manage the documentation from the terminal, during programming

this is the FlatEdit to help You manage the content of many projects


## Documentation [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/flatedit/examples/edit/main/DOCS/DOCS.md)

creating documentation is not easy in hundreds of small projects, where are dpendencies
we need some simple tool to manage the documentation from the terminal, during programming

this is the frlatedit:
+ file of projects list: readme.txt

### Dependencies

projects list [**readme1.txt**](readme1.txt)
```
./DOCS/MENU.md
../bash/DOCS/TODO.md
./DOCS/FOOT.md
```
[**readme.sh**](readme.sh)
```bash
./flatedit/readme.md readme1.txt
```

### Comments

With comments not to load this file

projects list [**readme2.txt**](readme2.txt)
```
./DOCS/MENU.md
../bash/DOCS/TODO.md
./DOCS/FOOT.md
```
[**readme.sh**](readme.sh)
```bash
./flatedit/readme.md readme2.txt
```


### Logs 

Show not- & working/existing files


projects list [**readme3.txt**](readme3.txt)
```
./DOCS/MENU.md
../bash/DOCS/TODO.md
./DOCS/FOOT.md
```
[**readme.sh**](readme.sh)
```bash
./flatedit/readme.md readme3.txt
```

## Install flatedit [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/flatedit/examples/edit/main/DOCS/INSTALL.md)


## Start

### install

```bash
./install.sh
```


### update

```bash
./update.sh
```


### remove

```bash
./remove.sh
```

## Contribution [<span style='font-size:20px;'>&#x270D;</span>](https://github.com/flatedit/examples/edit/main/DOCS/CONTRIBUTION.md)

Install dependencies after created project
```bash
curl https://raw.githubusercontent.com/apifork/bash/main/apifork.sh -o apifork
echo "apifork.dev.txt" > ".apifork"
echo "" > "apifork.txt"
echo "https://github.com/flatedit/bash.git flatedit" > "apifork.dev.txt"
apifork install apifork.dev.txt
```

Install dependencies after created project
```bash
curl https://raw.githubusercontent.com/apifork/bash/main/apifork.sh -o apifork
echo "https://github.com/flatedit/bash.git flatedit" > "apifork.dev.txt"
./apifork install apifork.dev.txt
```

Edit documentation with flatedit
```bash
echo '#!/bin/bash' > "readme"
echo './flatedit/readme.sh readme.txt' >> "readme"
echo "./DOCS/MENU.md" >> "readme.txt"
echo "./DOCS/ABOUT.md" >> "readme.txt"
echo "./DOCS/FOOT.md" >> "readme.txt"
```

### Update documentation

```bash
 ./readme
```

Config project file

The config file: **.apifork** can be another, e.g. **projects.txt**

Just change the first line in  **.apifork** on **projects.txt**
```bash
projects.txt
```


### install

[minsungson/GitHub-cURL: A guide to installing files from GitHub repos in terminal using cURL](https://github.com/minsungson/GitHub-cURL)

```bash
./apifork install
```
OR

```bash
./apifork
```

### update

```bash
./apifork update
```


### remove

```bash
./apifork remove
```



# Tags

+ scripts
+ language

---

+ [edit](https://github.com/flatedit/examples/edit/main/README.md)
+ [flatedit/examples](https://github.com/flatedit/examples)
