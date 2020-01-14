# Course Git

## git trabalha com três estágios

### 1 - arquivo que não esta vendo versionado

 ```
  git status
 ```

  <img src="git-status.png" class="center" style="display: block;
  margin-left: auto;
  margin-right: auto;
  width: 80%;"/>

### 2 - arquivo sendo adicionado e versionado

```
  git add readme.md
```

<img src="git-add.png" lass="center" style="display: block;
  margin-left: auto;
  margin-right: auto;
  width: 80%;"/>

### 3 - arquivo sendo commitado

```
  git commit -m "adding readme"
```

<img src="git-commit.png" lass="center" style="display: block;
  margin-left: auto;
  margin-right: auto;
  width: 80%;"/>

#### adiciona todos os arquivos a serem commitados

```
git commit -a -m "message"

```

#### mostra os logs

```
  git log
```

<img src="git-log-1.png" lass="center" style="display: block;
  margin-left: auto;
  margin-right: auto;
  width: 80%;"/>

#### mostra log em linha

```
  git log --pretty=oneline
```

<img src="git-log-pretty.png" style="display: block;
  margin-left: auto;
  margin-right: auto;
  width: 80%;">

#### mostra o log do que foi mudado

```
  git log -p
```

<img src="git-log-p.png" tyle="display: block;
  margin-left: auto;
  margin-right: auto;
  width: 80%;">
