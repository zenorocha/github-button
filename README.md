# &lt;github-button&gt;

Web Component wrapper for [@mdo's GitHub button](https://github.com/mdo/github-buttons) using Polymer.

## Demo

![GitHub Element](http://zno.io/QtpO/github-element.png)

> [Check it live](http://zenorocha.github.io/github-button).

## Usage

1. Import Web Components' polyfill:

	```xml
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```

2. Import Custom Element:

	```xml
	<link rel="import" href="src/github-button.html">
	```

3. Start using it!

	```xml
	<github-button></github-button>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`user`     | *string*                  | `customelements`    | GitHub username that owns the repo
`repo`     | *string*                  | `github-button`     | GitHub repository to pull the watchers/forks counts
`type`     | `follow`, `fork`, `watch` | `watch`             | Type of button to show
`count`    | `true`, `false`           | `true`              | Show the number of watchers/forks
`height`   | *int*                     | `25`                | The height of the button
`width`    | *int*                     | `100`               | The width of the button

> See GitHub Buttons' [official documentation](https://github.com/mdo/github-buttons).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* [v0.1.2](https://github.com/zenorocha/github-button/releases/tag/0.1.2) September 6, 2013
	* Rename element from `<github>` to `<github-button>`
	* Rename repo from `github-element` to `github-button`
* [v0.1.1](https://github.com/zenorocha/github-button/releases/tag/0.1.1) September 3, 2013
	* Use Polymer from CDN and update it to v0.0.20130816
* [v0.1.0](https://github.com/zenorocha/github-button/releases/tag/0.1.0) August 20, 2013
	* Initial development release
* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://zenorocha.mit-license.org/) © Zeno Rocha