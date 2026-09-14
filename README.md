# When Worn web release

Upload these three files together to the root of the GitHub/Firebase website:

- `index.html`
- `manifest.webmanifest`
- `when-worn-icon.png`

Keep the filenames unchanged. The HTML continues to use the existing
`rotationWardrobeDB` browser database, so replacing the old page does not
intentionally clear a returning user's locally saved wardrobe.

On iPhone, open the deployed site in Safari, choose **Share**, then
**Add to Home Screen**. On Android, open it in Chrome and choose **Install app**
or **Add to Home screen**. Both use `when-worn-icon.png`, the same supplied
When Worn artwork used by the Expo app.

The account, subscription, referral, cloud sync, and payment screens are
clearly labelled previews. They do not create accounts, charge users, or sync
data. Photo suggestions run in the browser and download public model files on
first use; results must be reviewed by the user.
