# Angular testing... but faster!

Thanks to everyone that came out to my talk at Day of the Programmer on Sept 10. It was a ton of fun! Below you’ll find a PDF version of the slides.

If you’ve randomly stumbled on this repo, and haven’t seen the talk, feel free to ping me about having a talk!

## About the talk
For better or worse Angular comes with a very opinionated set of tools. Fortunately just like an opinionated partner you can kick them to the curb them and move on!

We’ll start by discussing how to write good tests for an Angular front end. What sort of tests we can write, and how those look with the default tooling. After trying out the Karma setup that ships in the Angular box we’ll discuss some drawbacks of this setup.

Once we’ve explored testing in Angular, we’ll then discuss leaving those tools for Jest. We’ll discuss what Jest is, as well as our motivation for breaking from the norm.

## About the slides
The PDF attached here looks significantly different from the slides presented however all of the material and links are the same.  I hope you enjoy it!


## Bonus Materials

As requested at the end of the talk, I've added some "Bonus" materials here.  Namely I've included a .vscode folder with some nice extensions, a couple of settings, and some launch configs.

Nice Plugins:
- **prettier**
  Prettier provides automatic opinionated code formating.  We *love* this tool as it means that we don't get random changes between commits of whitespace etc, and we end up with nice standard easy to read code.
- **debugger-for-chrome**
  Debugger for chrome is a bit of a must have plugin if you're working with angular (or some other frontend web framework).  It allows you to launch a chrome window that is attached to vscode.  This means that you can set breakpoints in vscode, and hit them when you browse your site in the associated chrome window.  I can't imagine life without it.

Launch configs:
- **Chrome Debug**
  This will launch a new window of chrome, with the debugger attached to vscode so you can hit breakpoints.  It expects your app to be served on `localhost:4200` but you can of course change this.
- **Jest All**
  Run all jest tests, note the `--runInBand` this forces Jest to run all of your tests one by one and not parallelize them.  Which of course is useful if you don't want to have a debugging headache.
- **Jest Current File**
  This is by far my favorite config, it allows you to simply press *F5* when you have a test file open, and jest will run this file with full debug support.  Note how it simply passes the current file name to Jest as an argument, which of course you can also do on the command line.


## Contact

If you have questions, want to hear this talk again, or need some consulting help feel free to be in touch!

I'm always happy to answer questions or to come by and help you get your team working in a more efficient way!

[LinkedIn](https://www.linkedin.com/in/stephenlaumalmo/)