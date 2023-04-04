# Usage

Update this pull request title to:

Next release, bump theme version v{{ current_version_number }} -> v.x.x.x

This branch serves as a place to keep all developement intended to be added to the next theme release.

All features/fixes that will be released in this themes next release should target "next-release" as a merge target when creating a pull request.

Once a feature/fix has been approved and merged into this branch the list beneath [In this release](#in-this-release) needs to be updated.


Once a release is ready to be made follow the instructions in [Creating a release](#creating-a-release).

## In this release

Items are prefixed with either [new] or [fix] if applicable for styling within the changelog on our [website](https://fluorescent.co/help/stiletto/changelog).
If an item is linked to a nolt issue append the item with a nolt link: "[new] Add custom section padding [Nolt](https://lorenza-theme.nolt.io/)"

Exmaple changes:

- _[new] Description of change_
- _[fix] Description of change_
- _Other description of change_

Changes

- [new]

## Submitting a release

Before merging we will need to submit our new updates to Shopify and have them approved.

Using this branch follow the following instructions:

## Todo before submission

- [ ] Update `release-notes.md` to reflect the list of "Changes" beneath [In this release](#in-this-release). This will include categorizing them and adding a version description
- [ ] Update the version number in package.json
- [ ] Update the version number in this pull requests title: Next release, bump theme version v{{ current_version_number }} -> v.{{ new_version_number }}
- [ ] Run `yarn package` locally and install the theme via the zip created. Ensure the version number is accurate and the release not changes are in place
- [ ] Attach the zip file to this pull request under [Theme file](#theme-file)
- [ ] Submit to Shopify through the Fluorescent Design Inc. partners dashboard. Copy the [In this release](#in-this-release) changes into the update notes
- [ ] Update the _Submitted to Shopify date_ under [submission-date](#submission-date)

## Theme file

## Submission date
_Submitted to Shopify {{ date }}_

## Creating a release

Once these changes are approved by Shopify and released we can cut a github release.

## Todo before merge

- [ ] Shopify has approved the new theme update and has published the new version
- [ ] Copy the list of changes from [In this release](#in-this-release)

## Post merge release steps

- Then create a new github release pasting in the contents copied above
- The new release tag will be  `v{{ new_version_number }}`
- The new release title will be `{{ new_version_number }}`
- Paste the release notes copied above into the description. Ensure they are displayed as list items: `- [new] Add feature`
- Add the approved theme zip found under [Theme file](#theme-file) into the release binaries
- Publish release

---

Merge all features/fixes into this branch. Merge once a feature/fix is finished, this will make any further development include the previous changes. Once a feature is merged, pull down this development branch and start your next branch off of it. Once all features/fixes are ready to be release, merge this branch into master and create a release.