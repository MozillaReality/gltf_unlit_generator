# glTF Unlit Generator

Generates an unlit texture for each of the materials in a .gltf file.

## CLI Usage

```
cargo install gltf_unlit_generator
npm install -g gltf-unlit-generator
gltf-unlit-generator ./mygltf.gltf -o ./out
```

```
Usage: gltf-unlit-generator <gltfPath> [options]

  Options:

    -V, --version            output the version number
    -o, --out <out>          The directory to output the gltf and textures.
    -l, --lighten <lighten>  Scalar value 0.0 - 1.0 to be added to the RGB channels of the base color map.
    -h, --help               output usage information
```