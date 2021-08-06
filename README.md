# studies
site for essays and other content for EBT translation.

This site is built with Rocket, courtesy of Modernweb.


## contributing essays

Once you are set up to add essays, it's easy. They can be simply pushed to this Github repo, or if preferred, send to Sujato.

Submitted essays *must* follow the following form.

- Essays are in markdown: `foo.md` 
    - Use CommonMark. If you are not familiar, [take ten minutes to learn it](https://commonmark.org/help/tutorial/).
    - Check a [sample essay](https://raw.githubusercontent.com/suttacentral/studies/main/docs/essays/sujato/a-few-rather-insignificant-notes-on-the-dhammika-sutta-that-you-can-mostly-likely-live-without.md)
- Fill in the metadata fields as best as you can, delete or add more as you see fit. 
- Use Unicode, no special characters etc.
    - take special care to use Latin Ā not Greek Ᾱ when spelling Ānanda!
- Observe typographical niceties:
    - “curly quotes” not "straight quotes"
    - ellipsis … not three dots ...
    - em-dash—like this—for sentence breaks
    - en-dash for ranges (10–20)
- You can use any HTML in the markdown file for things not possible in Markdown. 
     - For an example of this, see the [Tipitaka Table](https://pali-studies.netlify.app/texts/tipitaka/) page. There I created a complex nested list, styled it, and allowed it to break out of the normal page width.
- With care, you can add you own CSS in the Markdown file. Beware that added styles apply globally, so ensure they are well-scoped with classes.
    - To style a single file, add `<style>p {color: red} </style>` immediately after the main heading.
    - To style multiple files, add `<link rel="stylesheet" href="/foo.css">` after the main heading and submit a CSS file in the same folder as the essays.
