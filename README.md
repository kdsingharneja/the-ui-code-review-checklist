# The User Interface Revivew Checklist

## Preface
As UI engineers and UI Architects we are chugging out code for new functionality or refactoring existing ones. Code reviews on those are fine and dandy, but many simple-small-stupid issues slip through. By the time they to quality assurance team, they become tickets and a cost gets associated with them. They become part of official technical debt, regardless of how fast you known them down. 

This checklist is intended to give you a comprehensive if not definitive list of items to look for if you are an engineer who pairs up witha peer to have your UI work reviewed. 

## Checklist

### General

* UI functionality conforms the UX mock ups (if any)

* Make sure the new pages are consistent with the old ones, unless you are redesigning the UI completely

* On the areas around your changes, check for 
	* paddings
    * margins
    * alignment with relative elements

* Messages that user will see on successful/failed interactions

* Labels (localized ones too if in place)

* Unless an informative icons or text is clickable, they should not have cursors.

* There should be a consitent spinner or loader icon for long processes

* Prefer pagination if list of items is going to make the user scroll

### Responsiveness

* The webpage is responsive for different viwe posts. Use Chrome plugin such as [Window Resizer](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh?utm_source=gmail) or [Browserstack](https://www.browserstack.com/). If done per proper responsiveness design the UI should show up properly on:
	- iPad
    - 5" Android Phone
    - Latest iOS models
    - 7" Tablets
    - Desktop
    - Wide screen monitors.

* Left hand menus become hamburger menus

* Text inputs do not dance around when screen is made responsive.