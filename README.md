# Proto-extractor

## Usage
*Tested on macOS only.*
```bash
git clone https://github.com/Krosbox/proto-extractor.git
cd proto-extractor/mono-extractor
msbuild
mono bin/Debug/mono-extractor.exe --proto3 \
--libPath $KROSBOX_DATA/Managed \
--outPath ../output  $KROSBOX_DATA/Managed/core-protocol-csharp-arena.dll
```

Original `README.md` -> [here](https://github.com/HearthSim/proto-extractor/blob/ff890981088108192acc68fe8a92c4cec7724e0c/README.md)
