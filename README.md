# iphonesite
iPhone mockup

## Kelvin's feedback

### Text Editor
Start doing good practices with our text editor.
- Use spaces over tabs
- Update your settings to auto insert spaces when you press the tab
- People use something called [editorconfigs](https://editorconfig.org/) to unify file/text formats across projects
- Sublime is great but getting outdated, switch over to [Visual Studio Code](https://code.visualstudio.com/)

### Git
- Get better at checking what you are going to commit before you commit it
- Learn great git practices by reading and following this [tutorial](https://www.atlassian.com/git/tutorials/what-is-version-control). Start on beginner and then onwards.
- Read up on good git practices [here](https://github.com/trein/dev-best-practices/wiki/Git-Commit-Best-Practices)
- Use a tool to help you visualize what you're doing. Use [Github Desktop](https://desktop.github.com/) or my personal favorite, [SourceTree](https://www.sourcetreeapp.com/)

### HTML feedback
#### Good
- No glaring issues, structure is good, no big issues
- Good job with comments

#### Bad
- Sectioning, spacing isn't very good. Could be better
- Inconsistent naming conventions for class names and id's
- Empty columns, those are almost never needed unless to maintain a set size all the time and content can come in and out anytime

#### Things to discuss
- Templates
- This is a plain HTML, web servers usually serve this up nowadays
- Web 1.0 vs Web 2.0, vs Web 2.5, etc.

### CSS feedback
#### Good
- It works, and it's straightforward

#### Bad
- Lots of repeated styles
- Naming conventions could be better
- Add proper formatting (space before brackets, etc)
- You used a library like bootstrap, which has some freebies of existing definitions, you could use that instead of writing your own new ones
- Useless CSS properties like col-left, col-left2, etc. You already have a grid system, what's the purpose of this?
- `calc` is sort of an emergency setup, not as cross browser compatible

#### Things to discuss
- Talk about containers, how they were used before, and have sort of been replaced with flexbox
- Setting up utility classes that can be used sitewide, without having to repeat yourself
- Talk a bit more about preprocessors
- caniuse.com
