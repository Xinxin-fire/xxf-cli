English | [简体中文](./README.md)

<p align="center"><img width="100" src="https://vuejs.org/images/logo.png"></p>

<h2 align="center">xxf-cli（A simple front-end CLI tool）</h2>
<p align="center"><b>Generate personal front-end scaffolding based on Node construction（vue）</b></p>
# 目录

- [feature](#feature )
- [QuickStart](#QuickStart)
  - [Install](#Install)
  - [Usage](#Usage)
- [Contribution](#Contribution)
- [Maintainers](#Maintainers)
- [License](#license)

### feature

- Easy to use
- Support custom template addition and deletion

### QuickStart

### Install

```bash
$ npm i xxf-cli -g               # install cli
$ omi init my-app     # init project, you can also exec 'omi init' in an empty folder
$ cd my-app           # please ignore this command if you executed 'omi init' in an empty folder
$ xxf init [templateName] [yourProjectName]
```

Install description:

The default scaffolding template name is vue-admin
> xxf init vue-admin [yourProjectName]

### New template usage

```bash
xxf add
# Select template and template address (github address)
```


-Note: The template address is the git repository name. The master branch is pulled by default.
  If you want to specify a branch, please use **owner / name # my-branch**

### Remove template usage

```bash
xxf delete
# 选择模板
```



### See all template usage

```bash
xxf list
```

### Initialize project scaffolding usage

```bash
xxf init 或者 xxf init [templateName] [yourProjectName]
```



## Contribution
- Xinxin-fire

## Maintainers

- [Xinxin-fire](https://github.com/Xinxin-fire/xxf-cli)

## License

- [MIT](https://opensource.org/licenses/MIT)
