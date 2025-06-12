# StorePreset Examples

This repository provides example store presets for [Sylius StoreAssembler](https://github.com/Sylius/StoreAssembler),
enabling you to quickly bootstrap themed Sylius shops with predefined data and assets.

## Usage

1. Copy your chosen preset directory from `store-presets/` into the root of your Sylius Standard project.
2. Run the StoreAssembler command to prepare and load the store preset:

   ```bash
   vendor/bin/store-assembler
   ```

This command will install any required plugins, load fixtures, and apply theme assets.

## Available Presets

- **car_parts**: A sample store for automotive parts, complete with product fixtures, images, and theme files.

## Contributing

Contributions are welcome! To add your own store preset:

1. Create a new folder under `store-presets/` following this structure:

   ```
   your_preset/
   ├── fixtures/
   │   ├── fixtures.yaml
   │   └── images/
   │       └── <your_image_files>
   ├── store-preset.json
   └── themes/
       └── shop/
           ├── banner.png
           └── logo.png
   ```

2. Submit a pull request with your preset and a brief description.

By contributing, you agree to license your changes under the MIT License.

## License

This project is released under the MIT License. See [LICENSE](LICENSE) for details.
