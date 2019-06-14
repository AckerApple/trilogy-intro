## Trilogy Exam
Acker Apple steps up to the plate to test his skills against the Trilogy intro exam.

[DEMO PAGE](https://ackerapple.github.io/trilogy-intro/)

## Development Commands
Open a command terminal and use any of the following commands

> You must have NodeJs install and have a very basic understanding of CLI commands

```
$ npm run install
```
```
$ npm run build
```
```
$ npm run watch
```

## GOALS

- no js framework
  - written vanilla js as position was mentioned as such
- SEO friendly
  - no at runtime compilation process
  - no angular, no vue, no react
- Produce readable code
  - Files are not reduced to one line
  - Anyone can read any part of the code
- Use one css framework
  - [ack-css-boot](https://www.npmjs.com/package/ack-css-boot)
    - [examples page](https://ackerapple.github.io/ack-css-boot/)

## Things to Know
- The required fonts are loaded remotely
  - Fonts could be embed as to avoid requests to google for fonts
- The provided icon SVGs have been reexported
  - Original svg icons did NOT have same centering
  - Originals would not fall on same display baseline
- The provided logos do NOT match the logos in mockups and style guides
  - If you stare hard enough, you can see a difference in triangle shape shades
  - 100% correct logos are needed
- Chevrons on mobile small screen are close but not 100% accurate in degree of pitch
- Section underlines are not 100% exact
  - spacing from word not 100%
    - css underline under moves underline too far
    - An absolute positioned border element could be used
      - wrapping text is a big concern with this "trick"
    - Recommend finding alternative or work together to get it right
  - Safari does not support solid underline that was used
    - possible webkit only declaration exists
- Fonts are not 100%
  - Highly advice against using fixed PX sizes
    - Relative sizes were used (em and %)
      - Far more compatible with individual devices
- FAQ in desktop mode
  - A floating element technique was used to avoid crashing text into laptop on tablet size like displays


## Other Exam Comparisons

Other people have taken this exam. Quite a lot. Searching github.com for keywords of this exam reveal many participants.

- https://github.com/Harrison1/gatsby-tril
  - does not appear to be SEO friendly
  - has demo
    - https://harrison1.github.io/gatsby-tril/
  - very large build
  - parts of design do not follow style guide
  - has (most) content and has fonts
    - Some content is not correct
    - Double verify any content used here

- https://github.com/derazmus/TrilogyCodingTest
  - no demo
  - misses the mark in replicating the styles
  - unfinished
  - does not break between mobile and desktop

- https://github.com/ColeSantiago/coding_landing_page
  - demo
    - https://colesantiago.github.io/coding_landing_page/
  - text clips into images making text hard to read
  - does not break down to mobile well
  - SEO friendly

- https://github.com/mchave10/trilogylandertest
  - no demo
  - no readme

- https://github.com/TommyHubbard/trilogy-landing-page
  - no demo

- https://github.com/gpeach/trilogyed
  - no demo