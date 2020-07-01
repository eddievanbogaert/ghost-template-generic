# Ghost Generic Theme Template

## For More Information

* [Ghost v3 Documentation](https://ghost.org/docs/)
* [Bootstrap v5 Documentation](https://v5.getbootstrap.com/docs/5.0)

## Quick Start for Local Testing and Development on macOS

**Install Ghost CLI**:
`npm install ghost-cli@latest -g`

**Install Local Instance**:
`ghost install local` (from empty directory)

**Clone Theme Package from Template Repository**:
`git clone https://github.com/eddievanbogaert/ghost-template-generic.git`

**Install Theme Dependencies**:
`npm install && ghost restart`

**Compile Sass Customizations to CSS**:
`npm run css-compile`

**Optimize and Map CSS Files**:
`npm run css-prefix`

**Restart Ghost Instance**:
`ghost restart` (rebuilds with changes)

**Watch for HTML/SCSS Changes and Automate Local Build Steps**:
`npm run watch`