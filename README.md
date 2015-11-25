#Info

These email snippets were created for Sublime Text 3

##Instructions

###Head to the top menu

Sublime Text > Preferences > Browse Packages

 Navigate to the Users file (e.g. \AppData\Roaming\Sublime Text 3\Packages\User) and clone git repo. Snippet should now be available to use.


###Use Snippets

To use the snippets simply type the required snippet in your HTML/CSS from the list and press tab to print the snippet.

Continue tabbing to run through changeable information within the snippet

```yaml

email
#This will bring up the latest email boilerplate from SaleCycle.

table-fluid
#Inserts a new fixed to fluid table. Declare initial width by tabbing.

table-fix
#Adds spacing fixes to your tables using an inline style tag.

table-cell-fix
#Adds spacing fixes to your table cells using an inline style tag. If the cell contains text, do not apply this fix.

ghost
#Adds the ghost comment fix. If you're floating two tables next to each other this will ensure they are put into fixed cells for outlook.

img-email
#Adds image containing specifically for email

spacer
#Adds spacer row. Tab to customise.

link-reset
#Pop this within your 'a' tag to reset link styles, colour selectable by tabbing.

mob-img-html
#Adds two table rows containing vanishing desktop image and hidden mobile image. Tab to edit.

mob-img-css
#Adds css for mob-img-html.

font-fam
#Adds a font family into your css. Tab to edit.

rec-items
#Adds base code for Recommended Items C2 Section. Colours/Fonts/Widths/Heights will need to be adjusted to your design.

```

###Key Binding
To wrap a section name around a block of html we've created a key bind. Add the following keybind to Sublime.

Sublime>Preferences>Key Bindings - User

```yaml 

[
  { "keys": ["alt+space"], "command": "insert_snippet", "args": {"name": "Packages/User/email-snippets/commentWrap.sublime-snippet" }}
]


```

###Use Keybind

```yaml

Select block of html. Hold Alt+Space to trigger the comment. Tab to name section wrap, this will add a name to the start of the comment and the end of the comment

```







