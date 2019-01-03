# Proto-extractor

## Usage
*Tested on macOS only.*
```bash
git clone https://github.com/Krosbox/proto-extractor.git
cd proto-extractor/mono-extractor
msbuild
mono bin/Debug/mono-extractor.exe --automatic-packaging \
--libPath $KROSBOX_DATA/Managed \
--outPath ../output \
$KROSBOX_DATA/Managed/core-protocol-csharp-arena.dll $KROSBOX_DATA/Managed/core-protocol-csharp-catalog.dll $KROSBOX_DATA/Managed/core-protocol-csharp-collection.dll $KROSBOX_DATA/Managed/framework-protocol-csharp-common.dll
```

Original `README.md` -> [here](https://github.com/HearthSim/proto-extractor/blob/ff890981088108192acc68fe8a92c4cec7724e0c/README.md)
