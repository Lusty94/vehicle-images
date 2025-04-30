# 🚗 Lusty94 Vehicle Images

- This repository contains remote vehicle images used in ``lusty94_rental``
- These images are served directly via raw GitHub URLs to support dynamic vehicle rental menus and other features.




## 🔧 How to Use

- In your config file for lusty94_rental, reference the vehicle image like this:

```lua
vehicles = {
  [1] = { 
      model = 'asbo', -- vehicle spawn name
      label = 'Asbo', -- label for menu
      description = 'Small, nimble and reliable!', -- description for menu
      price = 100, -- price to rent vehicle per minute
      image = 'asbo.png', -- vehicle image name on github link
      requiredTier = 0, -- 0 = no membership required
  },
}
```

The script will then fetch the image from:
https://github.com/Lusty94/vehicle-images/tree/main/images/asbo.png

## 🧾 Image Requirements
- If you'd like to add new images for other vehicles:
- Resolution should be 256x256 or lower preferred (keep file size low)
- Format: .png
- Naming: Use the vehicle model name in lowercase, e.g. bison.png, sanchez.png
- Save in images folder root of this repo (no subfolders)


## 🛠️ Contribute Your Own Images (Pull Request)

- Fork this repository
- Upload your image(s) to the root of your fork
- Make a Pull Request (PR) back to main with:
``
A clear title (e.g. Add image for banshee and dominator)
A short description
``
Done! If approved, your image will be usable by everyone instantly.


## 💬 Questions?
- Open an issue or reach out on [Discord](https://discord.gg/BJGFrThmA8) if you're not sure how to format or contribute.
