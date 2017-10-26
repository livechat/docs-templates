# Docs Changelog Guidelines

## How to make a good changelog? 

1. Changelogs are for **humans**, not machines.
2. There should be an entry for **every version**.
3. The same types of changes **are be grouped**. [See sections](#sections).
4. The latest version comes first, the release dates are displayed.

_Source: [Keep a Changelog](http://keepachangelog.com/en/0.3.0/)_

## Sections

|  Section     | Section purpose                   |
| ------------ | --------------------------------- |
| `Added`      | new features                      |
| `Changed`    | changes in existing functionality |
| `Deprecated` | soon-to-be removed features       |
| `Removed`    | now removed features              |
| `Fixed`      | any bug fixes                     |
| `Security`   | in case of security issues        |
| `Unreleased` | to note down upcoming changes     |

## Template

```
### Unreleased
- New method `fetchPotatoes()` fetching potatoes; details at [the project page](#)

## [v0.2] - 2017-10-26

### Added
- New method `returnWeirdFace()` returning a random avatar URL for a anonymous customer
- New object `weirdFaces` used in `returnWeirdFace()` method

### Changed
- Renamed `textualCorrespondence` to `chat` as it seems more readable

### Removed
- Section about "changelog" vs "CHANGELOG".

### Fixed
- Fix Markdown links to tag comparison URL with footnote-style links.

...
```
