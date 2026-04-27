---
layout: default
---

### Guard Startup Blueprint

![GuardBP](https://raw.githubusercontent.com/Cereza-Sol/Cereza-Sol.github.io/refs/heads/main/assets/images/GuardBlueprint.png)

All guards are set up in two pieces, one is the guard itself, and the other being an adjustable "path" you can set to your liking in the level editor. This allowed for my level designer and I to work more efficiently together.

* * *

### Meow Blueprint
![MeowBP](https://raw.githubusercontent.com/Cereza-Sol/Cereza-Sol.github.io/refs/heads/main/assets/images/MeowBlueprint.png)

The meow ability is used to create a wave of sound around you, specifically targeting guards so they can check it out if they hear the noise. It has an easily adjustable cooldown rate / area size, as well as a connection to the UI to know when it is on or off cooldown.

* * *

### Treats Rotation Fix
![TreatsBP](https://raw.githubusercontent.com/Cereza-Sol/Cereza-Sol.github.io/refs/heads/main/assets/images/LootRotationBlueprint.png)

When making the treats the level designer and I agreed to give the box some visual flair as to not miss out on it or making it feel static, blending in with the world. When using the build in "rotating movement" component, the child spotlight in the class would also rotate with the box which we didn't want. The fix was to create a timeline function to only rotate the treat box, fulfilling the wanted flair without messing with the spotlight.

[Back](./)
