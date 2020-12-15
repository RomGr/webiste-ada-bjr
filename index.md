---
layout: default
---

# Introduction
Would it be possible to predict the kind of interaction (i.e. positive or negative) that one would have with another, based on their previous interactions? With the use of signed social network data, we thought that this challenge can be met. If this appears to be true, models predicting edge signs might help to better understand the psychology of signed interactions on social media. Matrix factorization could generates individual preference profiles for each user. These profile could be applied in further studies to disentangle the magnitude of effects suggested by theories on status, balance, and embeddedness.

# Research Questions
1. Are signed networks from different social media platforms alike in terms of additional graph-theoretical properties?
2. Are these networks efficient and do they have small-world properties?
3. Can we validate the claim made by Leskovec et al. that negative edges tend to connect dense positive clusters?
4. Is it possible to predict the sign of an edge accurately? What can such a models reveal about the psychology of signed interactions on social media?

# The datasets
The datasets used for this project are the ones used in [Leskovec et al.](https://dl.acm.org/doi/10.1145/1753326.1753532). They contain signed edges between users of three social medias: Wikipedia, Slashdot and Epinions. In addition, we are considering a similar dataset containing links between subreddits on Reddit. A subreddit is a community on the social media platform Reddit. In all these datasets, links between users are represented by a weight from a source, i.e. the user that is giving their opinion, to a target. The weight of such an edge can take value +1 or -1 (+1 representing a positive link, -1 representing a negative one). 

# Are signed networks from different social media platforms alike in terms of additional graph-theoretical properties?

<img style="float: right;" src="https://github.com/RomGr/webiste-ada-bjr/blob/main/images/results.jpg">

To answer this question, we replicated Table 3 of [Leskovec et al.](https://dl.acm.org/doi/10.1145/1753326.1753532). We've found that the Reddit dataset does not follow the same pattern as the other datasets when it comes to triad under- and overrepresentation of certain triad types. Indeed, triads with all-positive edges are underrepresented and all other types are overrepresented. This goes against both structural balance theory and its weaker variant (see original paper by Leskovec et al. for context). One could argue that a subreddit is not a person and thus not subjected to the same rules of social psychology. But it would have been quite plausible that the principle that "the friend of my friend is my friend" applies also to groups. We don't see any particular reason why two groups which are friendly with a third group should not be friendly with one another. Further research is needed to explain this observation.













Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
