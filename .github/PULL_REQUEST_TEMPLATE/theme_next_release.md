# Usage

See [Next-release](https://www.notion.so/fluorescentdesigninc/Next-release-941a304da9674a549a63a2c93743ecff?pvs=4) full documentation.

- [ ] Update title to `Next release, bump theme version v{{ current_version_number }} -> v.x.x.x`

## Change log

- [new] Add new feature
- [fix] Fix broken feature
- Update random feature

_Delete this line and the above examples when adding real change log items_

## Before submission

- [ ] Update `release-notes.md` to reflect the changes in this update. The change log items can be categorized. Further information can be found [here](https://www.notion.so/fluorescentdesigninc/release-notes-md-33639b74d76b425cab224b8b6e09b95f?pvs=4)
- [ ] Update the version number in package.json
- [ ] Update the version number in this pull requests title: `Next release, bump theme version v{{ current_version_number }} -> v.{{ new_version_number }}`

## Submission

Once the release is ready to be submitted to Shopify follow the steps at [Submitting a theme update](https://www.notion.so/fluorescentdesigninc/Submitting-a-theme-update-8fba3c6a4e2f48479082e1f0a25918b3?pvs=4) and update the following tasks on completion.

- [ ] Ensure `release-notes.md` has been updated.
- [ ] Ensure the version number has been updated, and is visible on templates displaying `[[versionNumber]]` (check `theme.liquid` in the `/build` folder after running `yarn build`)
- [ ] Test the theme on a store by uploading the theme zip. Make sure it loads properly, and that you can complete a purchase flow (navigate to a product, add to cart, and checkout)
- [ ] Submit to Shopify

## After submission

- [ ] Update the _Submitted to Shopify date_ under [submission-date](#submission-date)
- [ ] Upload the theme zip replacing _theme.zip_ under [theme-file](#theme-file)
- [ ] Get Shopify approval by way of Shopify publishing the theme update

## After approval

Once Shopify has approved and published the new theme version follow the steps at [Making a theme release](https://www.notion.so/fluorescentdesigninc/Making-a-theme-release-5c1cdb412c2a4e52b6ce604ec77329c3?pvs=4).

## Submission date<a id='submission-date'></a>

_Submitted to Shopify {{ date }}_
## Theme file<a id='theme-file'></a>

_{{ theme }}.zip_
