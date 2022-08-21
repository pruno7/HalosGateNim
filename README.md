# TartarusGateNim

A quick example of the Tartarus Gate technique in Nim

Modified my code from my [Halo's Gate technique](https://github.com/pruno7/NimGates/tree/HalosGateNim) and added [trickster0's Tartarus Gate technique](https://github.com/trickster0/TartarusGate)

## Usage

Just compile the code :

```Bash
nim c -d:mingw -passL:-Wl,--image-base --passL:-Wl,0x10000000 HalosGate.nim
```

## Demonstration

I did not have access to a security solution that implemented the hooks that this technique bypasses. So use it at your own risk.