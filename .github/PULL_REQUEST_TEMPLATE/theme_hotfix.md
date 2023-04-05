# Usage

See [Hotfix](https://www.notion.so/fluorescentdesigninc/Hotfix-107236578e864567b5ad7fce109cb286) for full documentation.

- [ ] Update this pull request title to `Hotfix, bump theme version v{{ current_version_number }} -> v.x.x.x`

## Change log

- [new] Add new feature
- [fix] Fix broken feature
- Update random feature

_Delete this line the above examples when adding real change log items_

_Add the issue that has been hotfixed. If applicable prefix items with [new] to denote new features or [fix] for bug fixes._

## Before submission

- [ ] Update `release-notes.md` to reflect the changes in this update. This includes updating the version number, description, and categorizing change log items. Follow the instructions at [Updating release-notes.md](https://www.notion.so/fluorescentdesigninc/Updating-release-notes-md-33639b74d76b425cab224b8b6e09b95f)
- [ ] Update the version number in `package.json`
- [ ] Update the version number in this pull requests title: `Next release, bump theme version v{{ current_version_number }} -> v.{{ new_version_number }}`

## Submission

Once this release is ready to be submitted to Shopify follow the steps at [Submitting a theme update](https://www.notion.so/fluorescentdesigninc/Submitting-a-theme-update-8fba3c6a4e2f48479082e1f0a25918b3?pvs=4) and update the following tasks on completion.

- [ ] Ensure `release-notes.md` has been updated. This includes the version number, description, and the categorized change log items.
- [ ] Ensure the version number has been updated in `package.json`, and is visible on templates displaying `[[versionNumber]]` (check `theme.liquid` in the `/build` folder after running `yarn build`)
- [ ] After creating a theme.zip using `yarn package`. Manually test the theme on a store by uploading the theme zip. Make sure it loads properly, and that you can complete a purchase flow (navigate to a product, add to cart, and checkout)
- [ ] Submit to Shopify

## After submission

- [ ] Update the _Submitted to Shopify date_ under the **Submission date** heading below
- [ ] Upload the theme zip replacing _theme.zip_ under the **Theme file** heading below

## Approval

- [ ] Get Shopify approval by way of Shopify publishing the theme update

## After approval

Once Shopify has approved and published the new theme version follow the steps at [Making a theme release](https://www.notion.so/fluorescentdesigninc/Making-a-theme-release-5c1cdb412c2a4e52b6ce604ec77329c3?pvs=4).

---

## Submission date

_Submitted to Shopify {{ date }}_
## Theme file

_{{ theme }}.zip_
