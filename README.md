# AEL Train without Airplane Icon

This is a resource pack designed for the [Minecraft-Transit-Railway](https://github.com/Minecraft-Transit-Railway/Minecraft-Transit-Railway) MOD, featuring a livery for the A-Train ARL train without the airplane icon.

## Train Specifications

- **Red waistline livery: Red waistline** (`#008d8d`) **, black windows**
- **Interior: No changes**
- **Train model support - A-train-AEL standard specification: 10 windows, 2 doors**

## Appearance

### Train Appearance Showcase

**Front view of train head (unchanged)**
![Front view](images/列车侧拍.png)

**Side view of train**
![Side view](images/列车侧面.png)

**Train interior view (unchanged)**
![Interior view](images/列车内饰.png)

## File Structure

```
resource_pack/
    ├── pack.mcmeta          # Metadata
    ├── pack.png            # Icon
    └── assets/
        └── mtr/
            ├── mtr_custom_resources.json  # Train configuration
            └── custom_directory/
                ├── a_train_ael_noicon.png  # Train texture
                └── custom_sign.png       # Sign texture
```

## Installation

1. Download this resource pack
2. Package the contents of the `resource_pack` folder into a ZIP file and copy it to Minecraft's `resourcepacks` directory:

   ```
   resource_pack/
    ├── pack.mcmeta          # Metadata
    ├── pack.png            # Icon
    └── assets/
        └── mtr/
            ├── mtr_custom_resources.json  # Train configuration
            └── custom_directory/
                ├── a_train_ael_noicon.png  # Train texture
                └── custom_sign.png       # Sign texture
   ```
3. Enable this resource pack in the game
4. Ensure the MTR mod is installed

## Compatibility

- **Minecraft version**: Supports 1.16 version
- **MTR mod version**: Supports 3.2.2, but also compatible with later versions (e.g., 4.0.2)

### How to resolve version incompatibility

Navigate to pack.mcmeta in the resource pack folder, where you'll see the following content:

```mcmeta
{
	"pack": {
		"pack_format": 6,
		"description": "AEL train with No Icon"
	}
}
```

Change the value of `"pack_format"` to your version number: Information from [Minecraft official wiki](https://minecraft.wiki/w/Resource_pack#pack.mcmeta)

|Version|Number|
| ------------------| -------|
|1.6.1 - 1.8.9|1|
|1.9 - 1.10.2|2|
|1.11 - 1.12.2|3|
|1.13 - 1.14.4|4|
|1.15 - 1.16.1|5|
|1.16.2 - 1.16.5|6|
|1.17 - 1.17.1|7|
|1.18 - 1.18.2|8|
|1.19 - 1.19.2|9|
|1.19.3|11-12|
|1.19.4|13|
|1.20 - 1.20.1|15|
|1.20.2|16-18|
|1.20.3 - 1.20.4|22|
|1.20.5 - 1.20.6|32|
|1.21 - 1.21.4|47|
|1.21.5|55|
|1.21.6 - 1.21.8|64|
|1.21.9 - 1.21.10|69.0|
|1.21.11|75.0|

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.