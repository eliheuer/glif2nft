# glif2nft

`glif2nft` is a CLI Rust program created by Eli Heuer at the 2022 Seattle Solana Hacker House event.
It started as a fork of glif2svg from the MFEK project. The program creates on-chain SVG images from individual .glif files in a UFO, and prepares them for minting as Solana NFTs.
For Ethereum NFTs the program can just export the SVGs and Ethereum NFTs can be built manually.

## Usage Instructions

You will need a UFO file to use this program. This repository inclues an example UFO file if you don't have one on your local machine and/or you just want to test the software quickly. See the `ufos` directory.

You will need Rust installed to compile this program.

from the command line, navigate to the root of this repository and run:

```
cargo run ufos/PrintShoppe.ufo/glyphs/R_.glif > R.glif
```

Replace `ufos/PrintShoppe.ufo/glyphs/R_.glif` with any `.glif` file you want from your own UFOs.
