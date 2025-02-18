# $̶$̶$̶-̶_̶_̶
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

*Weird movement #1*

```
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
    "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
```

*Weird movement #2*

```
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```

*Weird movement #3*

```
{
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-1"
}
```

*Weird movement #4*

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

*Breaks physics*

```
{
  "FLogNetwork": "7",
  "FFlagHandleAltEnterFullscreenManually": "False",
  "FIntFullscreenTitleBarTriggerDelayMillis": "3600000",
  "DFIntCanHideGuiGroupId": "32380007",
  "DFIntPhysicsAnalyticsHighFrequencyIntervalSec": "20",
  "DFIntMaxFrameBufferSize": "4",
  "DFIntS2PhysicsSenderRate": "250",
  "FFlagLuauSolverV2": "True",
  "DFIntMaximumFreefallMoveTimeInTenths": "1000",
  "FIntInterpolationAwareTargetTimeLerpHundredth": "110",
  "FFlagReplicateAnimationLooped": "False",
  "FFlagGraphicsFixMsaaInGuiScene": "True",
  "DFFlagSimSolverOptimizeLDLCache": "True",
  "FFlagEnableSceneAnalysis": "False",
  "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "20"
}
```

*Become short*

```
{
"DFIntMaxAltitudePDHipHeightPercent": "-100"
}
```

*Fling yourself #1*

```
{
"DFIntNewRunningBaseGravityReductionFactorHundredth": "2500"
}
```

*Fling yourself #2*

```
{
 "DFFlagSimHumanoidTimestepModelUpdate": "true",
 "DFFlagSimRefactorCollisionGeometry2": "true",
 "DFIntMaxAltitudePDHipHeightPercent": "-825000",
 "DFIntMaxAltitudePDStickHipHeightPercent": "2147483647",
 "DFIntMaximumFreefallMoveTimeInTenths": "-2147483648",
 "DFIntMaximumUnstickForceInGs": "10000000000",
 "DFIntNewRunningBaseGravityReductionFactorHundredth": "1000",
 "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-1323232",
 "DFIntUnstickForceAttackInTenths": "50",
 "FFlagEnablePhysicsAdaptiveTimeSteppingIXP": "true",
 "SFFlagBulletContactBreakOrthogonalThresholdPercent": "2147483647"
}
```

*Fling yourself #3*

```
{
  "DFIntMaxAltitudePDHipHeightPercent": "-1000",
  "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-200000",
  "SFFlagBulletContactBreakOrthogonalThresholdPercent": "2147483647",
  "DFIntMaxAltitudePDStickHipHeightPercent": "2147483647"
}
```

*Fling yourself #4*

```
{
  "DFIntMaxAltitudePDHipHeightPercent": "-5000",
  "DFFlagSimStepPhysicsImprovedSubStepping": "true",
  "SFFlagBulletContactBreakOrthogonalThresholdPercent": "-2147483647",
  "DFIntMaxAltitudePDStickHipHeightPercent": "2147483647",
  "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-10000000"
}
```

*High ladder-flicks*

```
{
 "DFIntNewRunningBaseGravityReductionFactorHundredth": "1000"
}
```

*Weird tp*

```
{
  "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-2147483648"
}
```

*R15 speedhack*

```
{
  "DFIntHipHeightClamp": "-7",
  "DFIntUnstickForceAttackInTenths": "-1"
}
```

*Ragdoll yourself*

```
{
  "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
  "FIntPGSAngularDampingPermilPersecond": "0"
}
```

*Really fast wall-glide*

```
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
    "DFFlagSimHumanoidTimestepModelUpdate": "True",
    "DFIntUnstickForceAttackInTenths": "-4"
}
```

*Prevents position tp*

```
{
    "DFIntRaycastMaxDistance": "2",
    "DFIntNewRunningBaseGravityReductionFactorHundredth": "1000"
}
```

*Ultimate desync*

```
{
"DFIntS2PhysicsSenderRate": "1",
"FIntPGSAngularDampingPermilPersecond": "0"
}
```

*Less knockback*

```
{
    "DFIntPhysicsImprovedCyclicExecutiveThrottleThresholdTenth": "-1",
    "DFIntGameNetLocalSpaceMaxSendIndex": "100000"
}
```

*Slightly higher jump*

```
{
"SFFlagBulletContactBreakOrthogonalThresholdPercent": "2147483647"
}
```

*Purely broken movement #1*

```
{
  "DFIntRaycastMaxDistance": "-110",
  "DFIntBulletContactBreakOrthogonalThresholdPercent": "-2147483647",
  "DFIntMaximumFreefallMoveTimeInTenths": "0",
  "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-1"
}
```
*Purely broken movement #2*

```
{
"DFIntAssemblyExtentsExpansionStudHundredth": "-10",
 "DFIntBulletContactBreakOrthogonalThresholdPercent": "-2147483648",
 "DFIntGameNetLocalSpaceMaxSendIndex": "100000",
 "DFIntMaxAltitudePDHipHeightPercent": "-5000",
 "DFIntMaxAltitudePDStickHipHeightPercent": "2147483647",
 "DFIntMaximumFreefallMoveTimeInTenths": "2147483648",
 "DFIntMaxMissedWorldStepsRemembered": "1000",
"DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-10000000",
 "DFIntSmoothTerrainPhysicsRayAabbSlop": "-2147483648",
 "SFFlagBulletContactBreakOrthogonalThresholdPercent": "-2147483647"
}
```

*Become paralysed*

```
{
  "DFIntMaxAltitudePDHipHeightPercent": "-700",
  "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-1",
  "SFFlagBulletContactBreakOrthogonalThresholdPercent": "-2147483647",
  "DFIntMaxAltitudePDStickHipHeightPercent": "2147483647"
}
```

*Prevents remote events from running*

```
{
"DFIntRemoteEventSingleInvocationSizeLimit": "1"
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

*Turn the sky gray*

```
{
"FFlagDebugSkyGray": "True"
}
```

# Presets

*High quality graphics, lighting etc.*

```
{
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "3",
    "DFIntCanHideGuiGroupId":	"32380007",
    "DFIntTaskSchedulerTargetFps": "999",
    "FFlagDebugForceFutureIsBrightPhase3": "True",
    "FFlagDebugGraphicsPreferD3D11": "True",
    "FFlagRenderInitShadowmaps": "true",
    "FFlagDebugSkyGray": "True",
    "FFlagDebugRenderingSetDeterministic": "True"
}
```
