# Node JS Express Server Template

This repository serves as a template for Node JS server applications running on the [Express framework](https://expressjs.com/). These frameworks can be a little complicated to get started with since it isn't always just installing a single package like in other use cases. Frameworks such as Express are made up of many different components and sub-components. It isn't always obvious which packages you should install for a given project.

Thankfully the Express developers are aware of the complexities and offer a [generator tool](https://expressjs.com/en/starter/generator.html) for the terminal that can automatically initialize an Express server project with the necessary packages. You are also given options of what view engine to use for server-side rendering, such as [EJS](https://ejs.co/).

The generator tool is very useful at what it does but as somebody who works primarily in the back-end, I was a little confused by all of the different *view engines* on offer. Hence, I decided to create a repository that I can use as a template for Express APIs without having to refer back to the tutorial. It uses EJS for server-side rendering and vanilla CSS. I also included the `.gitignore` file.

---

## Usage

1. Clone the repository.
2. Run `npm install` to download the required packages.
3. Run the server using `SET DEBUG=njs-express-template:* & npm start`
4. Go to [localhost:3000](http://localhost:3000) to view the server home page.

Generated using the command: `npx express-generator --view=ejs --git`

---

## Disclaimer

This demo project is licensed under CC0 1.0 Universal. This is just a personal template for [Express.js](https://expressjs.com/) server applications that I have made available for public reference. This was created using the [express generator tool](https://expressjs.com/en/starter/generator.html). The generated server files are exactly as-is except for placeholder files added to empty folders. I do not claim any copyright over this template. The local files and the 3rd-party packages are property of their respective owners and I have no affiliation with them in any way.

As of December 2021, this repository is automatically updated with a [GitHub Actions](https://github.com/tjohnston-softdev/njs-express-template-updater) script on the first of every month at around 12PM UTC. In the event that something goes wrong with this process, I will manually correct it.

---