# Make Screenshots for App Stores
This is a script for Adobe Photoshop to to automatically save localized screenshots for App Stores.

![Dialog](make-screenshots-dialog.png)

### How to
1. Get Make `Screenshots.jsx`
2. Place it into  Photoshop scripts folder (`~\Adobe Photoshop CS6/Presets/Scripts/`)
3. Launch Photoshop
4. Open your appropriately structured file (see the sample)
5. Run script (`File->Scripts->Make Screenshots`)

## You will get
Here's the example file structure you'll get:
```
my_screenshots_folder/
      ├────/iPhone 6 Plus/
      │       ├────/EN/
      │       |     ├────/my_screenshot.jpg
      |       └────/DE/
      |             └────/my_screenshot.jpg
      ├────/iPhone 6/
      |       ├────/EN/
      |       |     └────/my_screenshot.jpg
      |       └────/DE/
      |             └────/my_screenshot.jpg
      └────/my_screenshot.psd
```       
### ToDo:
1. Requests?
