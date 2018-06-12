# Reify Command Line Interface

Reify CLI (reifycli) is a command line tool that lets developers crank out the basic scaffolding necessary for common React / Redux components.

Brief intro below.

## Dependencies

You'll need to have [node.js](http://nodejs.org/) installed (at least v6.0 or above) to install `reifycli` and run the `reify` command.

## Installation

#### Add the CLI package as a system-wide service
 - Run either:
   - `yarn global add reifycli` (preferred)
   - `npm install -g reifycli`

#### To use the CLI
 - Run `reify`
 - Follow the prompts to scaffold new React / Redux components in the local project being worked in.

#### Development
 - Clone this repo
 - `cd` into the folder
 - Run either:
   - `yarn install` (preferred)
   - `npm install`

 - _Developing the CLI_
    - Run `yarn start` from within the cloned repo folder.
    - This runs the CLI from the local source files.

 - _Using the unpublished-but-built source executable as a global module_
   - Run `npm install -g` from within the cloned repo folder.
   - This will install the __reify__ executable on your system (to then enable testing it in other projects, etc.).
