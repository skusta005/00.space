---
title: Abusive
icon: alert-fill
redirect: https://web.00xo.space/
order: -8
---
> [!CAUTION]
> FastFlags are not bannable by Roblox, but abusing them can get you banned from certain games.

### Teleport All Ragdolls/Unanchored to 0, 0, 0
> [!NOTE]
> Clientsided
```json
{
    "DFIntGameNetLocalSpaceMaxSendIndex": "10000"
}
```
### No Knockback/Ragdoll
```json
{
    "DFIntGameNetLocalSpaceMaxSendIndex": "100000",
    "DFIntPhysicsImprovedCyclicExecutiveThrottleThresholdTenth": "0"
}
```
### Tool Desync
```json
{
    "DFIntSimBlockLargeLocalToolWeldManipulationsThreshold": "-1"
}
```
### Remap R6 to R15 Rigs/Weird Movement
```json
{
    "FFlagRemapAnimationR6ToR15Rig": "True"
}
```
### Weird Leg Movement
```json
{
    "DFFlagAnimatorPostProcessIK": "True"
}
```
### Drunk
```json
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999"
}
```
### No Animations ✨
> [!NOTE]
> **Stops the game from trying to replicate your animations in the server. You dont have animations in the server but you do for your client**
```json
{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```
### Delayed Animations
```json
{
    "FFlagProcessAnimationLooped": "False"
}
```
### Stick unanchored parts to you
> [!TIP]
> **- = up, + = down**
```json
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```
### Max Raycast Distance
> [!NOTE]
> **Raycasting is the use of intersection tests to solve problems in Roblox. The most common use of raycasting is to determine the first object intersected by a ray. This is done by casting a virtual ray from a certain point in a direction and determining the first surface it intersected with.**

> [!TIP]
> **Break legs collision from 2 to -inf, kinda break camera on values over 3 noclip cam on 3**
```json
{
    "DFIntRaycastMaxDistance": "3"
}
```
### Change DataSender Rate
> [!NOTE]
> **A.k.a does not let you load games**
```json
{
    "DFIntDataSenderRate": "-1"
}
```
### Disable Touch Events
```json
{
    "DFIntTouchSenderMaxBandwidthBps": "-1"
}
```
### Improved Syncing
```json
{
    "DFIntS2PhysicsSenderRate": "10000"
}
```
### Invisible 1
```json
{
    "DFIntGameNetOptimizeParallelPhysicsSendAssemblyBatch": "-1",
    "DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "-1"
}
```
### Invisible 2
```json
{
    "DFIntPhysicsSenderMaxBandwidthBps": "1",
    "DFIntPhysicsSenderMaxBandwidthBpsScaling": "0"
}
```
### Clientsided Invisible
```json
{
    "FIntParallelDynamicPartsFastClusterBatchSize": "-1"
}
```
### Warp ✨
```json
{
    "DFIntMaxMissedWorldStepsRemembered": "1000"
}
```
### Mesh Noclip ✨
@tyetonix
```json
{
    "DFIntPhysicsDecompForceUpgradeVersion": "1500"
}
```
### Slide on Terrain/Meshes
@tyetonix
```json
{
    "DFIntSmoothTerrainPhysicsRayAabbSlop": "-9999"
}
```
==- Ability to walk
```json
{
    "DFIntSmoothTerrainPhysicsRayAabbSlop": "-9999",
    "DFIntMaximumFreefallMoveTimeInTenths": "2147483647"
}
```
===
### Wallglide ✨
found by discord userid: 784354759841939506
 ```json
 {
     "DFIntMaximumUnstickForceInGs": "-10"
 }
 ```
### Network Ownership
> [!NOTE]
> better [network ownership](https://create.roblox.com/docs/physics/network-ownership) of parts

> [!CAUTION]
> **This might get you banned in some games with anticheats (Limbobbia)**
```json
{
    "DFIntMinClientSimulationRadius": "2147000000",
    "DFIntMinimalSimRadiusBuffer": "2147000000",
    "DFIntMaxClientSimulationRadius": "2147000000",
    "DFFlagDebugPhysicsSenderDoesNotShrinkSimRadius": "True",
    "FFlagDebugUseCustomSimRadius": "True"
}
```
### Drive Vehicles Slow
 @tyetonix
```json
{
    "DFIntPhysicsImprovedCyclicExecutiveThrottleThresholdTenth": "0"
}
```

# Abusive Visuals

### Semi Fullbright
```json
{
    "FFlagFastGPULightCulling3": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "FFlagNewLightAttenuation": "True",
    "FIntRenderShadowmapBias": "-1",
    "DFFlagDebugPauseVoxelizer": "True"
}
```
### Draws a circle under avatars
```json
{
    "FFlagDebugAvatarChatVisualization": "True",
    "FFlagEnableInGameMenuChromeABTest4": "False",
    "FFlagEnableInGameMenuChrome": "False",
    "FFlagEnableInGameMenuSongbirdABTest": "False"
}
```
### Humanoid Outline
> [!NOTE]
> **Draws an outline around every part and every humanoid**
```json
{
    "DFFlagDebugDrawBroadPhaseAABBs": "True"
}
```
### fflag above but more complex
> [!NOTE]
> **Draws an outline around every body part**
```json
{
    "DFFlagDebugDrawBvhNodes": "True"
}
```
### Buggy ZPlane Camera ✨
```json
{
    "FIntCameraFarZPlane": "1"
}
```
### Adds an UI in game, which highlights any part player touches (like ground, Meshes etc.). It's a non-functioning UI too. Also adds a blue circle to your humanoid.
```json
{
    "FFlagDebugHumanoidRendering": "True"
}
```
