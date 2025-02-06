# Usage

Refer to [Next-release]([https://www.notion.so/fluorescentdesigninc/Next-release-941a304da9674a549a63a2c93743ecff?pvs=4](https://www.notion.so/fluorescentdesigninc/GitHub-branches-941a304da9674a549a63a2c93743ecff?pvs=4#191835388f1c80ebbb23dd788fc61668)) for full documentation.

- [ ] Update this pull request title to `Next release, bump theme version v{{ current_version_number }} -> vX.X.X`

## Before submission

- [ ] Determine the new version number. Refer to [Theme versioning](https://www.notion.so/fluorescentdesigninc/Theme-versioning-191835388f1c801d8846f5bf74500bcf?pvs=4) for more information.
- [ ] Update `release-notes.md` to reflect the changes in this update.
  - Each issue's PR handles adding to the release notes file (`src/release-notes.md`). At this point the list should be complete and just needs a pass to make sure everything is accurately included and correctly formatted. Mainly, this means updating the version number and description. Refer to [Release notes](https://www.notion.so/fluorescentdesigninc/Release-notes-33639b74d76b425cab224b8b6e09b95f?pvs=4#192835388f1c802dafefe31a13d246ce) for more information.
- [ ] Update the version number in `package.json`
- [ ] Update the version number in this pull requests title: `Next release, bump theme version v{{ current_version_number }} -> v.{{ new_version_number }}`

## Submission

Once this release is ready to be submitted to Shopify follow the steps at [Submitting a theme update](https://www.notion.so/fluorescentdesigninc/Submitting-a-theme-update-8fba3c6a4e2f48479082e1f0a25918b3?pvs=4#192835388f1c8004b948f658659082c4) and update the following tasks on completion.

- [ ] Ensure `release-notes.md` has been updated. This includes the version number, description, and the categorized change log items.
- [ ] Ensure the version number has been updated in `package.json`, and is visible on templates displaying `[[versionNumber]]` (check `theme.liquid` in the `/build` folder after running `yarn build`)
- [ ] After creating a theme.zip using `yarn package` (be sure to run `yarn` first). Manually test the theme on a store by uploading the theme zip. Make sure it loads properly, and that you can complete a purchase flow (navigate to a product, add to cart, and checkout)
- [ ] Submit to Shopify

## After submission

- [ ] Update the _Submitted to Shopify date_ under the **Submission date** heading below
- [ ] Upload the theme zip replacing _theme.zip_ under the **Theme file** heading below

## Approval

- [ ] Get Shopify approval by way of Shopify publishing the theme update

## After approval

Once Shopify has approved and published the new theme version:

- [ ] Follow the steps at [Finalizing a theme update]([https://www.notion.so/fluorescentdesigninc/Making-a-theme-release-5c1cdb412c2a4e52b6ce604ec77329c3?pvs=4](https://www.notion.so/fluorescentdesigninc/Submitting-a-theme-update-8fba3c6a4e2f48479082e1f0a25918b3?pvs=4#e78e069dd19749e2b0ce2adb8e2fb8ac)).
- [ ] Check for any Nolt requests that are addressed by this release and change their status to "Complete".

### Nolt requests

A list of any Nolt requests that are addressed by this release.

- 

#### Nolt "Complete" response templates

<details>
  <summary>Eclipse</summary>
  <p><strong>TODO:</strong> Add the changelog link once we publish one.</p>
  
  ```
  We’ve just published this feature in the newest version of Cornerstone!

  For a complete list of changes, check out Eclipse's changelog here: https://help.fluorescent.co/eclipse/readme/changelog
  And here’s where you’ll want to look for update instructions: https://cornerstone.help.fluorescent.co/theme-updates
  If you have any questions or issues, please message our support team at help@fluorescent.co.

  Thanks for your patience!
  ```
</details>

<details>
  <summary>Cornerstone</summary>
  
  ```
  We’ve just published this feature in the newest version of Cornerstone!

  For a complete list of changes, check out Cornerstone's changelog here: https://help.fluorescent.co/cornerstone/readme/changelog
  And here’s where you’ll want to look for update instructions: https://cornerstone.help.fluorescent.co/theme-updates
  If you have any questions or issues, please message our support team at help@fluorescent.co.

  Thanks for your patience!
  ```
</details>

<details>
  <summary>Stiletto</summary>
  
  ```
  We’ve just published this feature in the newest version of Stiletto!

  For a complete list of changes, check out Stiletto's changelog here: https://fluorescent.co/help/stiletto/changelog
  And here’s where you’ll want to look for update instructions: https://fluorescent.co/help/stiletto/theme-update
  If you have any questions or issues, please message our support team at help@fluorescent.co.

  Thanks for your patience!
  ```
</details>

<details>
  <summary>Spark</summary>

  ```
  We’ve just published this feature in the newest version of Spark!

  For a complete list of changes, check out Spark's changelog here: https://fluorescent.co/help/spark/changelog
  And here’s where you’ll want to look for update instructions: https://fluorescent.co/help/spark/theme-update
  If you have any questions or issues, please message our support team at help@fluorescent.co.

  Thanks for your patience!
  ```
</details>

<details>
  <summary>Lorenza</summary>
  
  ```
  We’ve just published this feature in the newest version of Lorenza!
  For a complete list of changes, check out Spark's changelog here: https://fluorescent.co/help/lorenza/changelog
  And here’s where you’ll want to look for update instructions: https://fluorescent.co/help/lorenza/theme-update
  If you have any questions or issues, please message our support team at help@fluorescent.co.
  Thanks for your patience!
  ```
</details>

---

## Submission date

_Submitted to Shopify {{ date }}_

## Theme file

_{{ theme }}.zip_
