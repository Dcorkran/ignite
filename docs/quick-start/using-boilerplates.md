# Using Boilerplates

You can use an boilerplate as the starting point for your app by creating a new
Ignite project with the `--boilerplate` flag:

```
ignite new MyIgniteApp --boilerplate {boilerplate name}
```

Ignite comes with a default boilerplate.

It creates your app with a host of opinions and options. This boilerplate reflects the way that we at Infinite Red prefer to start our apps. This is also Ignite's default boilerplate; if you don't select a one, Ignite will use this.

You can opt out of a boilerplate entirely by passing the option `--no-boilerplate`.  This will skip installing a boilerplate and only create a `ignite/ignite.json` file in your project; the bare minimum needed to become ignite sentient.

We intend to release new boilerplates as best practices change. For example, [React Navigation](https://reactnavigation.org) is a great new navigation library that we intend to support as soon as we feel it's ready. It will likely be released as a new boilerplate package, which in a future release of Ignite will be set to default once it's stable.

