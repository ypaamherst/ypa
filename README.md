Hi, Nick (and YPA team)!

I'd like to set expectations first: This isn't a web app to log into and edit content in Microsoft Word-like fields. It's not WordPress. And that's OK. Running a site on GitHub provides a simple, free hosting and maintenance solution that integrates directly into the codebase I created. It means other people can be given access to the project in the future, via their own GitHub accounts, and directly make changes **or** make changes under their own accounts and suggest them back to YPA. And if it gives everyone involved a little exposure to working with a website, that's good for everyone.

There's no server to maintain, no server accounts to maintain, no security to deal with, etc. It's a simple, editable HTML site. (More accurately, a Jekyll site, where Jekyll generates HTML from data and templates, but that's a bit deeper than anyone needs to worry about.)

With that said...

When you're logged in at GitHub, you should be able to access https://github.com/clearbold/ypa

There's a little dropdown at the top that should say `branch: gh-pages`. If it doesn't, choose that branch. `gh-pages` is the branch that powers the live website.

Below that is a list of all the folders and files in the site. You'll most often want to head to the `_data` folder.

Within that, you can click on `events.csv` or `exec-committee.csv`. Both are CSV data files, similar to those you might encounter in Excel.

### Editing Committee Members

If you click on `exec-committee.csv`, you'll see GitHub gives you a friendly view of the data in that file. There's a little pencil icon in the upper right you can click to edit the file.

Every value inside of `""` is a field, separated by commas. If you add new data, the number of fields must match the number of headers at the top, even if some are empty. You can cut & paste these rows of data to reorder them.

There's a green Commit Changes button at the bottom to save your work. If you make a mistake, don't worry! GitHub is version control software, so every change is recorded. You can roll back to a previous version.

Adding a Committee member would require uploading a new, cropped image, so we're not quite ready to support adding committee members without a bit of intervention.

### Editing/Posting Events

If you click on `events.csv` inside of `_data`, you see the events loaded up. Clicking the pencil icon will let you edit that data.

To add a new event, just copy an existing line, paste it in the right spot, and edit it accordingly. The first 3 events in the file will show on the website, with the first item in the middle, and the second and third on the left & right, respectively.

If you omit the link, with empty `""`, a link won't be applied on the site.

The timestamp field is just `yyyymmdd`.

### Editing the homepage

If you go back to the main file list and click on `index.html`, you'll see the HTML code behind the homepage.

Clicking the pencil icon will let you edit any of the content here. Some of the content here is matched up to specific formatting styles that might need a little intervention, but you can certainly make tweaks here.

You can email me with any questions, or, if you think we'd benefit from documenting a question and solution, click the Issues link on the main screen (over to the right) and post it to me there.

Enjoy!
