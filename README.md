
### Running the build
1. `bunx eas init` Setup and connect the project to Expo.
2. `bun install` install the dependencies
3. `bun run build` to build for the iOS simulator

You can you any other package manager you like.

Error

```
[RUN_FASTLANE] ❌  Undefined symbols for architecture x86_64
┌─ Symbol: _groth16_prover
└─ Referenced from: -[Rapidsnark groth16Prove:witnessData:proofBufferSize:publicBufferSize:errBufferSize:resolve:reject:] in libreact-native-rapidsnark.a[x86_64][2](Rapidsnark.o)

[RUN_FASTLANE] 
❌  ld: symbol(s) not found for architecture x86_64


[RUN_FASTLANE] 
❌  clang: error: linker command failed with exit code 1 (use -v to see invocation)
```