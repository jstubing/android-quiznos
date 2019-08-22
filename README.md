# android-quiznos
Sad about the boring Android 10 naming? This lib give you some options to spice things up.

# Usage

This lib gives you some extra `Build.VERSION_CODES` that you can use, pick whatever Q word you fancy

```kotlin
import me.tatarka.quiznos.Build

if (Build.VERSION.SDK_INT >= Build.VERSION_CODES.QUIZNOS) { .. }
if (Build.VERSION.SDK_INT >= Build.VERSION_CODES.QUECHE) { .. }
if (Build.VERSION.SDK_INT >= Build.VERSION_CODES.QUESITO) { .. }
if (Build.VERSION.SDK_INT >= Build.VERSION_CODES.QUEEN_OF_PUDDINGS) { .. }
if (Build.VERSION.SDK_INT >= Build.VERSION_CODES.QUEIJADAS) { .. }
```

Are you a fan of the boring naming? We got you covered too!

```kotlin
if (Build.VERSION.SDK_INT >= Build.VERSION_CODES.ANDROID_10) { .. }
if (Build.VERSION.SDK_INT >= Build.VERSION_CODES.TEN) { .. }
```