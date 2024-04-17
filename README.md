# Effect 3.0.0 failure on react-native

Included .apk and ios app builds made with expo application services

`npx expo start` to start the bundler

Run the app and it will crash with `TypeError: constructor is not callable` at [return new RequestResolverImpl(this.runAll, Chunk.fromIterable(ids))](https://github.com/Effect-TS/effect/blob/b2b5d6626b18eb5289f364ffab5240e84b04d085/packages/effect/src/internal/core.ts#L1767)
