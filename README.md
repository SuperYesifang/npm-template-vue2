# npm-template-vue2

![npm-template-vue2](https://img.shields.io/badge/npm--template--vue2-v1.0.0-%23C50008?logo=npm)
![vuejs](https://img.shields.io/badge/vuejs-v2.x-%234FC08D?logo=vuedotjs)
![nodejs](https://img.shields.io/badge/nodejs-lts--v14.x-%23036200?logo=nodedotjs)
[![blog](https://img.shields.io/badge/blog-yesifang.com-orange?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAMAAABEpIrGAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAABjFBMVEUAAAAIAQUiBhQVBA05CyK0I2z4MJTgKoV8GEoKAgZyFkT8MZfTKX4dBRFWEDP9MZfMJ3kGAQQHAQTlK4htFUEAHRMATDAAbUQAf1EAh1QAgFAAbUUATDAAHhNMDy7KJngAeUsAKBp9GEr4MJMDAQIAmWEAWzkABAOGGlD9MZYAcUgABQNoFD7mLIoAZUCdHl4ANiKiH2EpCBgAh1UAAgERAwrVKH9nFD0ALBwSAwuqIWXmK4pTEDIAWTgrCBp2F0eVHVmKG1NWETMAdEgAgVAAAQIAJTcATXIAZJQAbqUAap0AVoEAfE4AAQEAN1EAgMAAaEIACQ4Aap4ARiwACQ0AebMAmV8AEwwAAAAAZ5oAZT8AMkkAkFoAEQsAebMAl14AGCQAkl0ALx4AOlYAeEsAGRAATHAAbkUAll0All4AbkYAMB4ATXMABwQAIxYANiIAPicANyIAJBYAQF4AIjIAis0AAgMAhsYAZJYARWYAk9oAHy4ABQcAfbkAO1gAis3/MZgAmmEAld3///8EabibAAAAgHRSTlMACCIVObX54XwKcv3UHVb+zQYH5m0xfrTU4NW1fzJMy8hDffkD/pcHh/69CGjnqJ5ZoynfBBHWZ0kSqudTlCt2lotWwNUCQIOrvrWVzwFe3a4QtnQPz/0gAbKnVe4c0Psp9E9jximBtvj4t0+FCzpaZlo7bTruA+Wtdfs1CNdm7ZpKyEIAAAABYktHRIP8tM/SAAAAB3RJTUUH5QoVBh0NInrzjgAAATtJREFUOMt902VbwzAUBeDLcAYMhru7uzPcXYcP1+EyPMkvZ03TNk0TztfzNnL7BECeCFck/JOo6BiEYuPiVX2CG9EkJsn7ZA9iSUmV9d40ZCYdICMzKzsnNy+/wASFVo+KALCR4hIGSjlQVm4BXFFZRUE1B2q8HMC4tk4D9RxoABvAjRpwuS3QJADcrIkW6witImhrD4OOTtZ7ukAEuFtboqeXjqqvH5xgQL/qoG9oeET/FQIYdQxWAGNmMT4xOTU9MyuCOVbPLywSGhEs6f3yCiFysEr7tXWiABubWu/fIiqwTRfYISqwu0fBvgoc0DlCgCjA4ZF+hWMFODllMzizgfML2l5eXfuNGd7YAARv7+4fHoPc9J/swJlnrn+Rgdc3C4SkT+vd7D8+peDr2+h/FK838Ev3D4W//wNiKCWwWalJAwAAACV0RVh0ZGF0ZTpjcmVhdGUAMjAyMS0xMC0yMVQwNjoyOToxMyswMDowMP1Zb/cAAAAldEVYdGRhdGU6bW9kaWZ5ADIwMjEtMTAtMjFUMDY6Mjk6MTMrMDA6MDCMBNdLAAAAAElFTkSuQmCC)](//yesifang.com)

> 这不是一个可用的 npm 包，这是一个与 npm 包开发相关的 git 仓库，只是在 npmjs 上进行展示。
>
> 这是一个可用于发布 npm 包的 Vue2 组件开发工作空间模板。
>
> This is not an available npm package, this is a git repository related to npm package development and is just demonstrated on npmjs.
>
> This is a Vue2 component development workspace template that can be used to publish npm packages.

## Introduction

If you need to quickly build a vue2 component development workspace that can be published to npm, you can use the workspace template provided by npm-template-vue2.

## Usage

```shell
$ cd [your empty project folder path]
$ git clone git@github.com:SuperYesifang/npm-template-vue2.git .
$ rm -rf .git
```

**And then**

You just need to replace all the npm-template-vue2 in the project with your component name to start your component development.

**or**

If your linux or macos, you can also use the `sed`or`perl` command to complete the replacement.

## default Dependences

```json
{
	"dependencies": {
		"@babel/runtime": "^7.15.4",
		"vue": "^2.5.11"
	},
	"devDependencies": {
		"babel-plugin-transform-runtime": "^6.23.0",
		"babel-core": "^6.26.0",
		"babel-loader": "^7.1.2",
		"babel-preset-env": "^1.6.0",
		"babel-preset-stage-3": "^6.24.1",
		"cross-env": "^5.0.5",
		"css-loader": "^0.28.7",
		"file-loader": "^1.1.4",
		"vue-loader": "^13.0.5",
		"vue-template-compiler": "^2.4.4",
		"webpack": "^3.6.0",
		"webpack-dev-server": "^2.9.1"
	}
}
```
