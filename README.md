# Interface Utilities - Unity
_A package with utility classes to be able to drag and drop "interfaces" in Serialize Field_

## Installation
To install this package you can do one of this:~~~~
- Using Package Manager Window
    - Opening the Package Manager Window: Window > Package Manager
    - Wait for it to load
    - Click on the top left button `+` > Add package from git URL
    - Copy paste the [repository link](https://github.com/ErikRikoo/com.rikoo.interface-utilities.git)
    - Press enter

- Modifying manifest.json file
Add the following to your `manifest.json` file (which is under your project location in `Packages` folder)
```json
{
  "dependancies": {
    ...
    "com.rikoo.interface-utilities": "https://github.com/ErikRikoo/com.rikoo.interface-utilities.git",
    ...
  }
}
```

## Updating
Sometimes Unity has some hard time updating git dependencies so when you want to update the package, 
follow this steps:
- Go into `package-lock.json` file (same place that `manifest.json` one)
- It should look like this:
```json
{
  "dependencies": {
    ...
    "com.rikoo.interface-utilities": {
      "version": "https://github.com/ErikRikoo/com.rikoo.interface-utilities.git",
      "depth": 0,
      "source": "git",
      "dependencies": {},
      "hash": "hash-number-there"
    },
    ...
}
```
- Remove the _"com.rikoo.interface-utilities"_ and save the file
- Get back to Unity
- Let him refresh
- Package should be updated

## How does it work




## Suggestions
Feel free to suggest features by creating an issue, any idea is welcome !
