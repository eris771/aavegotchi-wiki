# The Official Wiki of Aavegotchi

##  How to Contribute

If you've never used Github before, you'll need to create an account. Then contact Coder Dan to get write access! 

#### Before you set up

You'll need to install `yarn` and `nodejs` onto your computer, via the command line. 

Yarn Install Guide: https://classic.yarnpkg.com/en/docs/install

NodeJS install guide: https://nodejs.org/en/download/

#### *Set-up Locally*
In your terminal, navigate to where you would like this blog to live, then run 
```bash
#clone the repo
git clone https://github.com/aavegotchi/aavegotchi-wiki.git

#navigate to the directory
cd aavegotchi-wiki

#install dependencies & run dev server with yarn 
yarn install
yarn dev

```

This will start a dev server, navigate to localhost:3000 to check it out.

#### *Edit and test*

Jump in and start building the Wiki! 

Changes in all the .tsx and .css files will appear without reloading the page.

Changes in Markdown (.md) files will require you to refresh the page. 

Once you're happy with your changes, submit a pull request and an Aarchiver will review and confirm. 

## Project Structure 

- Sidebar: `components/Sidebar`. 
- Global Styles `styles.css`. 
- Pages: `/p/[pageID]` fetches the Markdown file of the current page
