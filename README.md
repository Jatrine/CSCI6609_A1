# CSCI6609_A1

# Topic - Space

# Assets
1. Main Character: Free Animated Space Man (https://assetstore.unity.com/packages/3d/characters/humanoids/sci-fi/free-animated-space-man-61548)
2. Terrain: Lunar Landscape 3D (https://assetstore.unity.com/packages/3d/environments/landscapes/lunar-landscape-3d-132614#content)
3. Light: Unity Directional Light
4. Building: Magellan (https://assetstore.unity.com/packages/3d/vehicles/space/magellan-98970)
--- additional assets ---
5. Milky Way skybox (https://assetstore.unity.com/packages/2d/textures-materials/milky-way-skybox-94001)
6. Destructor Spaceship (https://assetstore.unity.com/packages/3d/vehicles/space/destructor-spaceship-3229)
7. Space SFX - 102218 (https://assetstore.unity.com/packages/audio/sound-fx/space-sfx-102218-131463)
8. Quick Outline (https://assetstore.unity.com/packages/tools/particles-effects/quick-outline-115488)
9. Unity Canvas

# Interactions
The character can rotate the viewpoint and move within the scene, with the option to select and destroy three black rocks.
1. Gyroscope: As the user holds the phone and turn in different directions, the viewpoint will rotate following the user's orientation.
2. Step Counter: The canvas on the left up corner indicates the step counted. When a step add up, the character will move a certain distance forward.
3. Touch Screen: If the user clicks on a destroyable rock, it will be selected (outlined yellow). Gyroscope and Step Counter are frozen in selection mode. Click on a selected rock again to deselect it.
4. Accelerometer: When a rock (or multiple rocks) is selected, the user can smash the phone downwards (be careful and hold the phone tightly!) to destroy the rock(s).

# Notes
1. Due to the GitHub file size limitation, library folder and the Asteroids Pack asset is not included.
2. References and resources to access Android Step Counter:
-https://www.reddit.com/r/Unity3D/comments/wjrg5q/how_to_use_the_pedometerstepcounter_sensor/
-https://github.com/yasirkula/UnityAndroidRuntimePermissions
-https://docs.unity3d.com/Manual/overriding-android-manifest.html