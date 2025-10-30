Save your profile image here as `profile.jpg` so the site loads it as the hero profile photo.

Steps:
1. Create the directory `assets` (if it doesn't exist) inside the project root: `mkdir -p assets`
2. Save the attached image (from the conversation) into `assets/profile.jpg`
   - Ensure the filename is exactly `profile.jpg` (lowercase)
3. Open `index.html` in a browser to verify the profile image appears in the hero section.

Notes:
- The image will be displayed as a circular portrait and cropped with `object-fit: cover`.
- If you prefer a different filename or location, update the `src` attribute in `index.html` accordingly.