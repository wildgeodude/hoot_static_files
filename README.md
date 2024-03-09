# Hoot

This repository hosts the static files for the [hoothq.com](https://hoothq.com) domain.

## How does Hoot work?
Hoot is a relatively simple browser extension.

It works a little bit like a website blocker. However in this case you the user have no control over which websites are blocked. The assumption is that if you've installed Hoot, you want all of this to be taken care of!

If you've got Hoot installed, when you navigate to a webpage the extension will use [this list](https://hoothq.com/symptom_checkers.json) of symptom checkers to work out whether to stop you in your tracks and prompt you to turn back.

## How to contribute
If you are here to to add items to the `symptom_checkers.json` file, please follow the below steps:
1. Fork this repo 
2. Make your edits to the `symptom_checkers.json` file
4. Submit a pull request ([docs for creating a pull request from a fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request-from-a-fork))

Pull requests for anything other than changes to `symptom_checkers.json` will be ignored and closed currently.

### What makes a good pull request?
Beyond your changes, it'd be useful to add some context. For example, if, as a contributor, I was submitting a change to add `https://example.com/symptom-checker` to the symptom checker file, I might also provide a description detailing that the main website is a general website about health and wellness. I might also consider adding that we don't want to completely block access to this site, but instead all pages under the `/symptom-checker` path. Therefore in my code changes I would add `https://example.com/symptom-checker/*`.

## How to raise an issue
Simply go to issues on this repository and submit a new issue. Please go into as much detail as possible.

## Credits
All emojis designed by OpenMoji – the open-source emoji and icon project. License: CC BY-SA 4.0
