# Boilerplate Play and Reactive seed

![CircleCI Build](https://circleci.com/gh/philihp/play-java-react-seed.png?circle-token=:circle-token)

A minimal seed template for a Play boilerplate project which uses React JSX components
which are precompiled on the server.

## Usage

At the command line, go to the dir where you want your project folder to be created and run

```bash
activator new MYPROJECT play-java-react-seed
```

That's all. Seriously. Now there's a project all ready for you. You can test running it by going into the folder and running it.

```bash
cd MYPROJECT
activator run
```
```
[info] Loading project definition from /Users/philihp/work/MYPROJECT
[info] Set current project to MYPROJECT (in build file:/Users/phil_busby/work/MYPROJECT/)

--- (Running the application, auto-reloading is enabled) ---

[info] play - Listening for HTTP on /0:0:0:0:0:0:0:0:9000

(Server started, use Ctrl+D to stop and go back to the console...)
```

and visit [http://localhost:9000](http://localhost:9000). You can see `/app/assets/javascripts/component.jsx` being rendered server-side by going to [http://localhost:9000/assets/javascripts/component.js](http://localhost:9000/assets/javascripts/component.js)
