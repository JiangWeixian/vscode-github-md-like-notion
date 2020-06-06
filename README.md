<div align='center'>

# @vscode-gh-md-like-notion

*a enhancer for github readme*

</div>


- [@vscode-gh-md-like-notion](#vscode-gh-md-like-notion)
	- [install](#install)
	- [config](#config)
	- [snippets](#snippets)
		- [description - `!description`](#description---description)
		- [description - `!description-with-center-logo`](#description---description-with-center-logo)
		- [inline-images - `!images-inline-{count}`](#inline-images---images-inline-count)
		- [image-with-caption - `!image-with-caption`](#image-with-caption---image-with-caption)
		- [image-with-center-caption - `!image-with-center-caption`](#image-with-center-caption---image-with-center-caption)
		- [table-react-component-props - `!table-react-props`](#table-react-component-props---table-react-props)
		- [inside-link - `!link`](#inside-link---link)
		- [outside-link - `!link-outside`](#outside-link---link-outside)
		- [backers - !backers](#backers---backers)
		- [contributors - `!contributors`](#contributors---contributors)
		- [badge-producthunt - `!badge-producthunt`](#badge-producthunt---badge-producthunt)
		- [badge-applestore - `!badge-applestore`](#badge-applestore---badge-applestore)
		- [badge-googleplay - `!badge-googleplay`](#badge-googleplay---badge-googleplay)
		- [button-sponsor-pateron - `!sponsor-pateron`](#button-sponsor-pateron---sponsor-pateron)
		- [tabs - `!tabs`](#tabs---tabs)
		- [single tab - `!tab-item`](#single-tab---tab-item)
		- [date - `!date or !date-YYYY/MM/DD`](#date---date-or-date-yyyymmdd)
		- [date with showtime - `!date-YYYY/MM/DD HH:MM:SS](#date-with-showtime---date-yyyymmdd-hhmmss)
		- [emoji - `!emoji-{gitmojiname}`](#emoji---emoji-gitmojiname)
		- [keyboard - `!keyboard`](#keyboard---keyboard)
		- [signature - `!signature`](#signature---signature)
- [](#)

## install

> ext install vscode-gh-like-notion

## config

**in settings.json**

```json
"[markdown]": {
	// ...
	"editor.quickSuggestions": {
			"other": true,
			"comments": false,
			"strings": false
	},
	// ...
},
```

## snippets

### description - `!description`

### description - `!description-with-center-logo`

<div align='center'>

![logo](https://avatars2.githubusercontent.com/u/6839576?s=460&u=ae20ee0b187d0c4f70cae7daa12ae09fb47b78a9&v=4)

*a enhancer for github readme*

</div>


### inline-images - `!images-inline-{count}`
> four-inline-image example

<a><img src='https://avatars2.githubusercontent.com/u/6839576?s=460&u=ae20ee0b187d0c4f70cae7daa12ae09fb47b78a9&v=4' width='216' /></a><a><img src='https://avatars2.githubusercontent.com/u/6839576?s=460&u=ae20ee0b187d0c4f70cae7daa12ae09fb47b78a9&v=4' width='216' /></a><a><img src='https://avatars2.githubusercontent.com/u/6839576?s=460&u=ae20ee0b187d0c4f70cae7daa12ae09fb47b78a9&v=4' width='216' /></a><a><img src='https://avatars2.githubusercontent.com/u/6839576?s=460&u=ae20ee0b187d0c4f70cae7daa12ae09fb47b78a9&v=4' width='216' /></a>

### image-with-caption - `!image-with-caption`

![avatar](https://avatars2.githubusercontent.com/u/6839576?s=460&u=ae20ee0b187d0c4f70cae7daa12ae09fb47b78a9&v=4 "avatar")

*avatar*

### image-with-center-caption - `!image-with-center-caption`

<div align="center">

![avatar](https://avatars2.githubusercontent.com/u/6839576?s=460&u=ae20ee0b187d0c4f70cae7daa12ae09fb47b78a9&v=4 "avatar")

*avatar*

</div>

### table-react-component-props - `!table-react-props`

|name|description|type|default|
|:---:|:---:|:---:|:---|
|props-a|a|string|just a test|

### inside-link - `!link`

[inside-link](https://github.com/JiangWeixian/vscode-github-md-like-notion)

### outside-link - `!link-outside`

[outside-link 🔗](https://github.com/JiangWeixian/vscode-github-md-like-notion)

### backers - !backers

<a href="https://opencollective.com/react-three-fiber#backers" target="_blank">
  <img src="https://opencollective.com/react-three-fiber/backers.svg?width=890"/>
</a>

### contributors - `!contributors`

<a href="https://github.com/react-spring/react-three-fiber/graphs/contributors">
  <img src="https://opencollective.com/react-three-fiber/contributors.svg?width=890" />
</a>

### badge-producthunt - `!badge-producthunt`

<a href="https://www.producthunt.com/posts/collaborative-markdown-editor?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-collaborative-markdown-editor" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.png?post_id=91983&theme=light" alt="Collaborative Markdown Editor - Collaborative editor with end-to-end encryption. | Product Hunt Embed" style="width: 250px; height: 54px;" width="250px" height="54px" /></a>

### badge-applestore - `!badge-applestore`

<a src=''><img width='180' alt='apple-appstore' src='https://user-images.githubusercontent.com/6839576/83937447-42f3e280-a7ff-11ea-9ca6-b20a0a8d3f09.png'></a>

### badge-googleplay - `!badge-googleplay`

<a src=''><img width='180' alt='googleplay-store' src='https://user-images.githubusercontent.com/6839576/83937448-44250f80-a7ff-11ea-8998-b97dc4fb2395.png'></a>

### button-sponsor-pateron - `!sponsor-pateron`

<a src='https://www.patreon.com/jiangweixian'><img width='180' alt='sponsor-pateron' src='https://c5.patreon.com/external/logo/become_a_patron_button@2x.png'></a>

### tabs - `!tabs`

[tab1]()・[tab2]()

### single tab - `!tab-item`

・[tab2]()

### date - `!date or !date-YYYY/MM/DD`

2020/06/06

### date with showtime - `!date-YYYY/MM/DD HH:MM:SS
`
2020/06/06 15:15:58

### emoji - `!emoji-{gitmojiname}`
> some useful emoji from [gitmoji](https://gitmoji.carloscuesta.me/)

- features - ✨
- bug - 🐛
- tada - 🎉
- wip - 🚧
- config - 🔧
- docs - 📝

### keyboard - `!keyboard`

<kbd>ctrl</kbd>

### signature - `!signature`

# 
<p align='right'>

*built with ❤️ by jiangweixian*

</p>
