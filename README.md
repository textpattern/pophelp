# Textpattern CMS help files

This repository contains Help files (aka 'Pophelp') for [Textpattern CMS](http://textpattern.com). These Pophelps are the translation file format Textpattern will eventually use in future versions.

## Specification

Structure:

```
help/
    {language}/
        {article}.html
```

Contents:

```html
<h2>Article title</h2>
<p>Body.</p>
```

## Contributing

To make corrections to existing translations, or to add new ones, [fork the repository](https://help.github.com/articles/fork-a-repo). Once you are done, send in [a pull request](https://help.github.com/articles/using-pull-requests).

### Contributing via GitHub web editor

GitHub's [web based editing features](https://help.github.com/articles/creating-and-editing-files-in-your-repository) allow you to easily do smaller edits to existing translations without you needing to delve into git. Changing files through the web interface isn't really recommended, but it's an option for those that do not use git, or are away from their computer.

To contribute to a translation directly from GitHub.com website:

1. [Sign in](https://github.com/login) with your GitHub account
2. Navigate to a Pophelp file you would want to alter, e.g. [help/en-gb/body.html](https://github.com/textpattern/pophelp/blob/master/help/en-gb/body.html).
3. Click or tap the **Edit** button above the presented file contents.
4. Make some alterations to existing text.
5. After you've done, fill in the short commit message describing the change, e.g. *"Fixed typo"*.
6. Click or tap the **Save** button.

Now to submit in a new pull request with your changes:

1. Click or tap the **Click to create a pull request for this comparison** link on the page presented to you after saving, or you can use the **Compare and pull request** button on your fork's repository page.
2. Fill in the comment field; explain what your changes do. Be precise and clear.
3. Click or tap the **Send pull request** button.

Once your pull request is processed and marked closed (merged or denied), go back to your GitHub profile page and delete your clone of the Pophelp repository:

1. Find the 'pophelp' repository on your profile page; it should be listed on your repository list.
2. Open it.
3. On the repository's page, click or tap the **Settings** link.
4. Scroll down until you see **Delete repository** button.
5. Click or tap it and confirm the action.

## License

Licensed under the [GPLv2 license](https://github.com/textpattern/pophelp/blob/master/LICENSE).
