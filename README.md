# Josh Martin's Personal Website
This is a website dedicated to Josh Martin. 

Here you'll find all the info I want the world to know!

# Local Development
## Brew
    brew install asdf
    brew install libyaml

## asdf
    asdf plugin add nodejs
    asdf plugin add pnpm
    asdf plugin add ruby
    asdf install
    // add to ~/.zshrc
    export PATH="${ASDF_DATA_DIR:-$HOME/.asdf}/shims:$PATH"

installs everything in the .tool-versions file. We'll use this to establish commands that can help us install and build


pnpm i 
- installs the gems defined in the gem file

pnpm serve
- launches a local server to see changes on your localhost