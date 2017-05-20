# react-scripts-passphere

Adds [CSS Modules](https://github.com/css-modules/css-modules) and other goodies to [Create React App](https://github.com/facebookincubator/create-react-app).

Either create a new project using
`create-react-app my-app --scripts-version react-scripts-passphere`
or within your existing project uninstall `react-scripts` and install `react-scripts-passphere`.

This package is 10:1 with Create React App. E.g. v0.9.10 of this package is the same as and interchanable with v0.9.1 of Create React App.

Any additional numbers are fixes for this app only. E.g. v0.9.21 is v0.9.2 of React App with a fix only for passphere.

See this [CRA Issue](https://github.com/facebookincubator/create-react-app/issues/682) for more details, or for a more indepth guide check out [this article](https://medium.com/@shubheksha/tweaking-configuration-for-react-scripts-in-create-react-app-d91e9d03a42f).

## Additional featues
	- CSS Modules and regualr CSS imports. Name any css modules <name>.modules.css
	- Only supports last 2 browsers + IE11.
