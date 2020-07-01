# Ghost Generic Theme Template

## For More Information

* Consult the [Ghost Documentation](https://ghost.org/docs/) for more information.

## Quick Start for Local Testing and Development on macOS

*Install Ghost CLI*
`npm install ghost-cli@latest -g`

*Install Local Instance* (from empty directory)
`ghost install local`

*Clone Theme Package from Template Repository*
`git clone https://github.com/eddievanbogaert/ghost-template-generic.git`

*Install Theme Dependencies*
`npm install && ghost restart`

*Compile Sass Customizations to CSS*
`npm css-compile`

*Optimize and Map CSS Files*
`npm css-prefix`

*Restart Ghost Instance* (rebuilds with changes)
`ghost restart`

*Watch for HTML/SCSS Changes and Automate Local Build Steps*
`npm run watch`