# Ionic2 AngularFire

This project is an Ionic2 app which loads data from Firebase using AngularFire2 which supports Observables.

Full documentation on how this project was created from a default Ionic2 app is available in [this blog post](https://medium.com/@tanya/ionic2-with-angularfire2-f0b0e2126cc7)


## Installation

Before running this app ensure you have the following global npm modules installed:

```
npm install -g ionic@2.1.0
npm install -g typescript@2.0.3
npm install -g cordova@6.3.1
```
Once your environment is set up do the following:

1. Clone this project
2. Run `npm install` to install all the modules
3. Update `src/app/app.module.ts` lines 11-15 to use your own Firebase config settings.
4. Update "items" in `src/pages/home/home.ts` line 16 to instead use a data set in your database.
5. Update `src/pages/home/home.html` line 11 to display a property of your own data.

Run the app using `ionic serve` from the command line.


## Contributing

If you would like to contribute a change via pull request please do the following:

- Do your work on a separate branch
- One change / fix / feature per pull request
- If you updated any package versions local or global please make this explicit
- Ensure you have also updated the ReadMe if required
- Small pull requests are more likely to be merged :)


