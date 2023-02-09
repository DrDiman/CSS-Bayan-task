| Deadline | Folder name | Branch name |
| ----------- | ------------- | ------------- |
|  | cssBayan | gh-pages |

# Task: CSS Bayan

You should create an accordion with HTML and CSS only.

<kbd>![screenshot](assets/accordion.png)</kbd>

## Functional requirements:
1. Design is at your discretion, but the layout of an accordion should include a meme image, text, and an icon. The placement of these elements should match the provided above example image;
2. Implement responsive design with three breakpoints. Accordion is displayed correctly at `mobile 320x568, tablet 820x1180, desktop 1920×1080`;
3. There should be icon for state of the expanded\collapsed item (you can choose your own icons e.g. from FontAwesome);
4. Implement visual effects when the cursor is hovering over the memes, when the mouse is down on a meme (moment of mouse down - for active effect);
5. Smooth transitions are applied for changing of memes and for changing of icon;
6. Make the entire row (text, icon, and meme image) clickable;
7. Mobile first approach is used - cursor over the memes (hover) effect exists only for desktop devices [MDN Note](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover);
8. Center the accordion component on the screen, with equal indents on the left and right;
9. Change the cursor when it is hovering over the accordion;
10. Initially, the first meme should be expanded (chosen/selected);
11. Font size should be changed at each device (mobile, tablet, desktop)

❗ If it's not clear how the accordion should behave - take a look at the Clarifications section below, recoded gifs and their scenarios.

## Clarifications - Accordion behavior:

### Note 1. commonHover.gif.
<kbd>![screenshot](assets/commonHover.gif)</kbd>

***Recorded scenario for desktop device:***
  - User moves cursor over the accordion (hover)
  - User removes cursor (hover) from the accordion

### Note 2. hoverOverItem.gif.
<kbd>![screenshot](assets/hoverOverItem.gif)</kbd>

***Recorded scenario for desktop device:***
  - the 4th meme is already chosen (clicked) by the user
  - User moves cursor over the accordion (hover) - over 4th meme
  - User moves cursor over 5th meme (hover)
  - User moves cursor over 4th meme (hover)
  - User moves cursor over 3rd meme (hover)
  - User moves cursor over 2nd meme (hover)
  - User moves cursor over 1st meme (hover)
  - User removes cursor (hover) from the accordion
  - the 4th meme stays be chosen

### Note 3. clickActiveItem.gif.
<kbd>![screenshot](assets/clickActiveItem.gif)</kbd>

***Recorded scenario for desktop device:***
  - the 4th meme is already chosen (clicked) by the user
  - User moves cursor over 4th meme (hover)
  - User moves cursor over 5th meme (hover)
  - User moves cursor over 4th meme (hover)
  - User moves cursor over 3rd meme (hover)
  - User moves cursor over 2nd meme (hover)
  - User clicks on the second meme. It becomes chosen (active, clicked). The 4th meme becomes not chosen
  - User removes cursor (hover) from the accordion

## Repository requirements and how to submit task:
1. Create public repository `cssBayan`
2. Create `gh-pages` branch (if you don't have)
3. Switched to it (gh-pages) and create folder called `cssBayan`. Your deployed accordion will be available,
    e.g.: `https://${YOUR_GITHUB_NAME}.github.io/cssBayan/cssBayan/index.html`
4. Implement your solutions in this folder (cssBayan). There should be at least **5** commits.
5. [You should call your commits accordingly to the guideline](https://docs.rs.school/#/git-convention) + Each your commit should contain time-stamp.

    5.1. Time-stamp can be at any language; Accordingly to your time-stamp should be clear: when this commit was done: day of the week, month, day, year, time with seconds (the order can vary) e.g. commit message:
> init: start cssBayan-task (Mon, Sep 13, 2021 10:12:24 PM)

> feat: add basic page layout (Mon, Sep 13, 2021 10:25:24 PM)

6. When the solution is ready - open Pull Request from `gh-pages` branch to `main` branch. Pull Request name should be equal to the task name. [Description of the Pull Request should be accordingly to the guideline](https://docs.rs.school/#/pull-request-review-process?id=%D0%A2%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-pull-request-pr). Do NOT merge this Pull Request. The link to this Pull Request should be submitted to the cross check form. Pull request should contain full description - what was done and what was skipped.

❗ Remember that if cross-checker has any potential questions to your accordion solution - he\she should find all the answers in the pull request description.

## How to check the task:

- The task will be checked with peers cross-check. [Cross-check instructions](https://docs.rs.school/#/cross-check-flow)

## Technical requirements:
- It's forbidden to use CSS frameworks (bootstrap, foundation and etc...);
- It's forbidden to use JavaScript and npm libraries;
- It's forbidden to use CSS preprocess tools (You should use pure CSS);
- Your accordion should work correctly in Chrome;
- It's allowed to use additional content e.g. h1, footer, header,... to increase content of the page;
- It's allowed to use `gif` images;
- It's allowed to use `px` for media queries;
- It's allowed to have automatic first commit, which is called `Initial commit` and created by Git Hub;
- It's allowed to use `reset.css` and `normalize.css`

## Criteria for estimation\evaluation

**Max score 140**

1. Everything is done from `Repository requirements and how to submit task` section **+30**
2. The accordion component is centered on the screen, with equal indents on the left and right **+10**
3. Icons, meme texts and meme images are exist **+5**
4. Placement of the meme, icons and meme text are the same as in provided example gif images **+5**
5. Smooth change (transition) of the meme images and icons is done **+20**
6. Responsive design with three breakpoints for mobile, tablet, and desktop exist. Accordion is displayed correctly at `mobile 320x568, tablet 820x1180, desktop 1920×1080` **+10**
7. All visual effects when the cursor is hovering over the memes, when the mouse is down on a meme, and when a meme is selected are implemented **+10**
8. The entire row (text, icon, and meme image) clickable **+5**
9. Mobile first approach is used - cursor over the memes (hover) effect exists only for desktop devices **+10**
10. The cursor when it is hovering over the rows of the accordion is changing **+5**
11. Only flexible dimensions are used `rem, em, %, vh, vw, fr` and etc... The accordion is responsive **+10**
12. All blocks/parts of the accordion are in base flow of the dom elements. All elements are not positioned with `top, left, right, bottom`. `float` is not used. The value of `position` is only `static` **+5**
13. Pseudo-elements are not used (note: pseudo-classes are allowed) **+5**
14. Initially, the first meme should be expanded **+5**
15. Font size is changed at each device (mobile, tablet, desktop) **+5**

## Penalty points/Fine:
- Usage of the JS scripts or any other libraries **-100500**
- Usage of the apfruscated (not human-readable) CSS/HTML **-100500**
- Cheating, peer copy pasting **-100500**

❗ Sizes of the each block, fonts, content and design are up to developer. Differences can vary significantly. The score do not downgrade for that. The main goal to save positions and behavior of the accordion and the other technical requirements.

❗ Feel free to create/find/choose memes by your own, but preferably at least 4 memes.

Good luck in creation of your own BAYAN =)
