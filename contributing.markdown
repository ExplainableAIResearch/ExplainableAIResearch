---
layout: page
title: Contributing
description: How to contribute to this website.
---

Contributions of new or missing publications are very welcome. Alternative categorization/taxonomies can also be added to the website. To contribute, please [open a pull request](https://github.com/ml4code/ml4code.github.io), but first please read the instructions below.

### Adding a publication
To add a publication (new or missing), create a file in the `_publications` folder. The name of the file should follow the structure `lastnameYEARfirstword.markdown` where `lastname` is the last name of the first author and `firstword` is the first non-punctuation word of the work's title. Within each file, follow the structure shown in the other files. Once the file is added, the work will appear in the "All Papers" section.
<pre>
---
layout: publication
title: The title of the Publication
authors: F. M. LastName, F. M. LastName, ...
conference: AbbreviatedNameOfConference
year: YEAR
additional_links:
   - {name: "ArXiV", url: "http://arxiv.org/abs/XXXX.YYYY"}
   - {name: "website", url: "http://paperwebsite.com"}
   - {name: "code", url: "https://github.com/path-to/code"}
tags: ["tag1", "tag2"]
---
Text of abstract goes here.
</pre>

The `additional_links` are optional and arbitrary and they will appear on the page referring to this work. Feel free to add as many additional links as needed.

