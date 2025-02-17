# FF.github.io
𝙏𝙝𝙞𝙨 𝙞𝙨 𝙖 𝙙𝙤𝙘𝙪𝙢𝙚𝙣𝙩𝙖𝙩𝙞𝙤𝙣 𝙤𝙛 𝙚𝙫𝙚𝙧𝙮 𝙛𝙖𝙨𝙩𝙛𝙡𝙖𝙜 𝙄 𝙝𝙖𝙫𝙚 𝙘𝙤𝙢𝙚 𝙖𝙘𝙧𝙤𝙨𝙨
𝙘𝙤𝙣𝙩𝙖𝙞𝙣𝙞𝙣𝙜 𝙦𝙪𝙖𝙡𝙞𝙩𝙮 𝙤𝙛 𝙡𝙞𝙛𝙚, 𝙋𝙝𝙮𝙨𝙞𝙘𝙨 𝙧𝙚𝙡𝙖𝙩𝙚𝙙 𝙛𝙖𝙨𝙩𝙛𝙡𝙖𝙜𝙨 𝙖𝙣𝙙 𝙑𝙞𝙨𝙪𝙖𝙡 𝙛𝙖𝙨𝙩𝙛𝙡𝙖𝙜𝙨.

___

# Quality Of Life

*Faster preloading*

```
{
    "DFIntNumAssetsMaxToPreload": "9999999",
    "DFIntAssetPreloading": "9999999"
}
```

*Limits lighting changes*

```
{
    "FIntRenderLocalLightUpdatesMax": "8",
    "FIntRenderLocalLightUpdatesMin": "6"
}
```
*Remove in-game advertisements*

```
{
    "FFlagAdServiceEnabled": "False"
}
```

*Disable telemetry*

```
{
    "FFlagDebugDisableTelemetryEphemeralCounter": "True",
    "FFlagDebugDisableTelemetryEphemeralStat": "True",
    "FFlagDebugDisableTelemetryEventIngest": "True",
    "FFlagDebugDisableTelemetryPoint": "True",
    "FFlagDebugDisableTelemetryV2Counter": "True",
    "FFlagDebugDisableTelemetryV2Event": "True",
    "FFlagDebugDisableTelemetryV2Stat": "True"
}
```

*Disable shadows*

```
{
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647"
}
```

*Reduce avatar particles in first person*

```
{
    "FFlagUserHideCharacterParticlesInFirstPerson": "True"
}
```

*Smoother terrain*

```
{
    "FFlagDebugRenderingSetDeterministic": "True"
}
```

*Disable player shadows*

```
{
    "FIntRenderShadowIntensity": "0"
}
```

*5 Decimal digits limit for camera sensitivty*

```
{
    "FFlagFixSensitivityTextPrecision": "False"
}
```

*Disable voicechat*

```
{
    "DFFlagVoiceChat4": "False"
}
```

*Disable dynamic head animations*

```
{
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0"
}
```

*Automatically unmute your mic when you join*

__(This is for vociechat)__

```
{
    "FFlagDebugDefaultChannelStartMuted": "False"
}
```

*Change zoom out limit*

```
{
    "FIntCameraMaxZoomDistance": "9999"
}
```

*Quick game launching*

```
{
    "FFlagEnableQuickGameLaunch": "True"
}
```

*Display your fps*

```
{
	"FFlagDebugDisplayFPS": "True"
}
```

*Stop purchase prompts*

```
{
	"DFFlagOrder66": "True"
}
```

*Accessory adjustment in roblox player beta*

```
{
"FFlagAXAccessoryAdjustmentIXPEnabledForAll": "True",
"FFlagAccessoryAdjustmentEnabled5": "True"
}
```

# Physics related FFlags

*Tool desync*

```
{
    "DFIntSimBlockLargeLocalToolWeldManipulationsThreshold": "-1"
}
```

*Adjust your hip height clamp (Only works with the mage animation in r15)*

__(Making the negative value bigger causes your hip height clamp to be higher)__

```
{
    "DFIntHipHeightClamp": "-48"
}
```

*Weird movement*

```
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
    "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
```

*No animation*

__(Only shown on the servers side)__

```
{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```

*Fling unanchored objects*

__(- Causes the objects to go upwards and + causes the objects to go downwards)__

```
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```

*Max raycast distance*

__(Breaks leg collision from -2 to inf, Kind of breaks camera on values above 3 and Noclip camera on 3)__

```
{
    "DFIntRaycastMaxDistance": "3"
}
```

*High jump*

__(Higher values cause you to bug out much more and have a higher jump)__

```
{
    "DFIntNewRunningBaseGravityReductionFactorHundredth": "1500"
}
```

*Disable touch events*

```
{
    "DFIntTouchSenderMaxBandwidthBps": "-1"
}
```

*Frame buffer*

```
{
	"DFIntMaxFrameBufferSize": "2"
}
```

*Fake lag*

__(This is only shown on the server's client)__

```
{
    "DFIntS2PhysicsSenderRate": "1"
}
```

*Invisibility #1*

__(Stops the physics requests from your character sending to the server, This causes your character on the server's client to stop moving whilst being able to move on your client)__

```
{
    "DFIntS2PhysicsSenderRate": "-30"
}
```

*Invisibility #2*

__(Freezes your character at the position 0, 0, 0 on the server's client)__

```
{
    "DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "10"
}
```

*Invisibility #3*

__(Basically the same as the first one but you can get toppled over by other people on the server's client)__

```
{
    "DFIntPhysicsSenderMaxBandwidthBps": "1",
    "DFIntPhysicsSenderMaxBandwidthBpsScaling": "0"
}
```

*Slow motion*

```
{
    "DFIntMaxMissedWorldStepsRemembered": "1"
}
```

*Warp*

__(This is too confusing to explain though it does have to do with tab glitching)__

```
{
    "DFIntMaxMissedWorldStepsRemembered": "1"
}
```

*Noclip #1*

__(Adjust the value so you dont fall through the ground)__

```
{
    "DFIntMaxMissedWorldStepsRemembered": "1"
}
```

*Noclip #2*

__(Adjust the value so you dont fall through the ground)__

```
{
"DFIntAssemblyExtentsExpansionStudHundredth": "-50"
}
```

*Consistent high jump*

__(The higher the negative value the higher you jump, 0 Makes you float)__

```
{
    "DFIntMaxAltitudePDStickHipHeightPercent": "-200"
}
```

*Wall glide*

```
{
    "DFIntUnstickForceAttackInTenths": "-4"
}
```

*Better network ownership*

```
{
    "DFIntMinClientSimulationRadius": "2147000000",
    "DFIntMinimalSimRadiusBuffer": "2147000000",
    "DFIntMaxClientSimulationRadius": "2147000000"
}
```

*Break most glitches*

```
{ 
"DFFlagSimHumanoidPhysics": "True"
}
```

*Become short*

```
{
"DFIntMaxAltitudePDHipHeightPercent": "-100"
}
```

*Fling yourself*

```
{
"DFIntNewRunningBaseGravityReductionFactorHundredth": "2500"
}
```

*High ladder-flicks*

```
{
 "DFIntNewRunningBaseGravityReductionFactorHundredth": "1000"
}
```

# Visusals

*Semi full-bright*

__(A bit buggy)__

```
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

*Outline hitboxes #1*

```
{
    "DFFlagDebugDrawBroadPhaseAABBs": "True"
}
```

*Outline hitboxes #2*

```
{
    "DFFlagDebugDrawBvhNodes": "True"
}
```

*Buggy z-plane camera*

```
{
    "FIntCameraFarZPlane": "1"
}
```

*Adds a in-game ui that shows what your character is touching*

```
{
    "FFlagDebugHumanoidRendering": "True"
}
```

*X-ray #1*

```
{
    "DFIntCullFactorPixelThresholdMainViewHighQuality": "10000",
    "DFIntCullFactorPixelThresholdMainViewLowQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "10000"
}
```

*X-ray #2*

```
{
  "DFIntCullFactorPixelThresholdMainViewHighQuality": "1250",
  "DFIntCullFactorPixelThresholdMainViewLowQuality": "1250",
  "DFIntCullFactorPixelThresholdShadowMapHighQuality": "1250",
  "DFIntCullFactorPixelThresholdShadowMapLowQuality": "1250",
  "DFIntDebugFRMQualityLevelOverride": "1"
}
```

**
