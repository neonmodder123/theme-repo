<div align="center">
  <br>
  <img src="https://user-images.githubusercontent.com/52459150/215552092-9dc1e029-da35-43da-867f-17279e3dc180.png" alt="Cowabunga Logo" width="200">
  <img src="https://github.com/rooootdev/lara/blob/main/lara.png?raw=true" alt="lara Logo" width="200">
</div>

# lara Cowabunga-theme-repo
Fork of the official Cowabunga theme repo for lara.

## How do I create a passcode theme repo?
`repo_name`: Your theme repo name, it will be displayed on the app

`repo_author`: The repo's author

`repo_icon`: The repo's icon, set it to a raw URL

`themes`: Your passcode themes

### In `themes`
`name`: Name of your theme

`description`: Description of your theme

`url`: Relative path to your theme. Ex. `passcode-themes/AmongUsKeylock.passthm`

`preview`: Preview PNG of your theme (to show how it looks like), set it as a relative path too

`contact`: How to contact you. Ex. `"contact": { "GitHub": "@NoW4U2Kid" }`

`version`: Theme version number

## Example passcode theme repo
```javascript
{
  "repo_name": "neonthemes",
  "repo_author": "neonmodder123",
  "repo_icon": "https://github.com/neonmodder123.png",
  "themes": [
    {
      "name": "Among Us",
      "description": "When the impostor is sus.",
      "url": "passcode-themes/AmongUsKeylock.passthm",
      "preview": "passcode-theme-previews/among_us.png",
      "contact": { "GitHub": "@NoW4U2Kid" },
      "version": "1.0"
    },
    {
      "name": "Adobe Dog",
      "description": "Funny dog from adobe stock photos.",
      "url": "passcode-themes/BEST_adobe_dog.passthm",
      "preview": "passcode-theme-previews/adobe_dog.png",
      "contact": { "GitHub": "@LeminLimez" },
      "version": "1.0"
    }
  ]
}
```

# Credits
- Cowabunga team
- Theme owners
- Anyone else I may have forgotten
