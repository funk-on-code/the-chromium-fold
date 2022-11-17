### The Chrom{e/ium} Command Line

## You may either add this to your /home/[user]/.config/chromium-flags.conf file, or add the string from the command line, as is your preference.

```
--block-new-web-contents --disable-background-networking --disable-breakpad --disable-crash-reporter --disable-default-apps --disable-domain-reliability --disable-external-intent-requests --disable-file-system --disable-webgl --extension-content-verification=enforce_strict --extensions-install-verification=enforce --gpu-rasterization-msaa-sample-count=0 --lite-video-force-override-decision --no-pings --num-raster-threads=4 --process-per-site --site-per-process --time-zone-for-testing=UTC --use-fake-device-for-media-stream --enable-features="BlockInsecurePrivateNetworkRequests,BlockInsecurePrivateNetworkRequestsForNavigations,BrowserDynamicCodeDisabled,DesktopScreenshots,DisableProcessReuse,ElementSuperRareData,EnableCsrssLockdown,EncryptedClientHello,ForceIsolationInfoFrameOriginToTopLevelFrame,GpuAppContainer,ImprovedCookieControls,IntensiveWakeUpThrottling:grace_period_seconds/10,IsolateOrigins,IsolatePrerenders,IsolateSandboxedIframes,MinimizeAudioProcessingForUnusedOutput,NetworkServiceSandbox,NetworkServiceCodeIntegrity,OpaqueResponseBlockingV01,OriginIsolationHeader,PartitionConnectionsByNetworkIsolationKey,PartitionDomainReliabilityByNetworkIsolationKey,PartitionExpectCTStateByNetworkIsolationKey,PartitionHttpServerPropertiesByNetworkIsolationKey,PartitionNelAndReportingByNetworkIsolationKey,PartitionSSLSessionsByNetworkIsolationKey,PartitionedCookies,PostQuantumCECPQ2,PrefetchPrivacyChanges,ReduceUserAgent,ReducedReferrerGranularity,RendererAppContainer,RestrictGamepadAccess,SandboxExternalProtocolBlocked,ScopeMemoryCachePerContext,SplitAuthCacheByNetworkIsolationKey,SplitCacheByIncludeCredentials,SplitCacheByNetworkIsolationKey,SplitHostCacheByNetworkIsolationKey,StrictOriginIsolation,SubframeShutdownDelay,SuppressDifferentOriginSubframeJSDialogs,ThirdPartyStoragePartitioning,ThrottleForegroundTimers,TurnOffStreamingMediaCachingAlways,TurnOffStreamingMediaCachingOnBattery,WinSboxDisableExtensionPoint,WinSboxDisableKtmComponent" --disable-features="AcceptCHFrame,AdInterestGroupAPI,AllowClientHintsToThirdParty,AllowURNsInIframes,AnonymousIframeOriginTrial,AutofillEnableAccountWalletStorage,AutofillServerCommunication,BrowsingTopics,ClearCrossSiteCrossBrowsingContextGroupWindowName,ClientHintThirdPartyDelegation,ClientHintsDPR,ClientHintsDPR_DEPRECATED,ClientHintsDeviceMemory,ClientHintsDeviceMemory_DEPRECATED,ClientHintsMetaHTTPEquivAcceptCH,ClientHintsMetaNameAcceptCH,ClientHintsResourceWidth,ClientHintsResourceWidth_DEPRECATED,ClientHintsViewportWidth,ClientHintsViewportWidth_DEPRECATED,ComputePressure,ContextMenuPerformanceInfoAndRemoteHintFetching,ConversionMeasurement,CookieDomainRejectNonASCII,CopyLinkToText,CrashReporting,CriticalClientHint,CrostiniAdditionalEnterpriseReporting,CssSelectorFragmentAnchor,DocumentReporting,EnableStructuredMetrics,EnterpriseRealtimeExtensionRequest,ExpectCTReporting,EnableTLS13EarlyData,FedCm,Fledge,FontAccess,GreaseUACH,IdleDetection,InterestGroupStorage,Journeys,LensStandalone,MediaDrmPreprovisioning,MediaEngagementBypassAutoplayPolicies,NavigationRequestPreconnect,NetworkTimeServiceQuerying,NotificationTriggers,OmniboxTriggerForNoStatePrefetch,OptimizationHints,OptimizationHintsFetching,OptimizationHintsFetchingAnonymousDataConsent,OptimizationHintsFieldTrials,Parakeet,Prerender2,PrefersColorSchemeClientHintHeader,PreloadMediaEngagementData,Reporting,RetailCoupons,SCTAuditing,SegmentationPlatform,SignedExchangeReportingForDistributors,SignedHTTPExchange,SpeculationRulesPrefetchProxy,SubresourceWebBundles,TabMetricsLogging,TFLiteLanguageDetectionEnabled,TextFragmentAnchor,SafeBrowsingBetterTelemetryAcrossReports,UserAgentClientHint,UserAgentClientHintFullVersionList,UsernameFirstFlow,UsernameFirstFlowFilling,UsernameFirstFlowFallbackCrowdsourcing,ViewportHeightClientHintHeader,WebNFC,WebOTP,WebSQLInThirdPartyContextEnabled,WebXR,WinrtGeolocationImplementation" --connectivity-check-url=0.0.0.0 --crash-server-url=0.0.0.0 --gaia-url=0.0.0.0 --gcm-checkin-url=0.0.0.0 --gcm-mcs-endpoint=0.0.0.0 --gcm-registration-url=0.0.0.0 --google-apis-url=0.0.0.0 --google-base-url=0.0.0.0 --google-doodle-url=0.0.0.0 --lso-url=0.0.0.0 --oauth-account-manager-url=0.0.0.0 --override-metrics-upload-url=0.0.0.0 --realtime-reporting-url=0.0.0.0 --reporting-connector-url=0.0.0.0 --sync-url=0.0.0.0 --url=0.0.0.0 --variations-server-url=0.0.0.0 --variations-insecure-server-url=0.0.0.0 --cipher-suite-blacklist="0xc013,0xc014,0x009c,0x009d,0x002f,0x0035" --js-flags=--jitless --blink-settings="dnsPrefetchingEnabled=false,preferredColorScheme=1,strictMixedContentChecking=true,strictMixedContentCheckingForPlugin=true,strictlyBlockBlockableMixedContent=true" --disable-blink-features="CrossOriginOpenerPolicyReporting,DirectSockets,HandwritingRecognition,IdleDetection" --isolation-by-default
```
## Documentation
<details><summary>Flags</summary><p>

| Name | Description |
| :--- | :---------- |
| --block-new-web-contents | Blocks all pop-ups |
| --cipher-suite-blacklist | Blocks lists of cipher suites |
| --disable-background-networking | Blocks background networking, like Safe browsing |
| --disable-breakpad | Disables the crash reporting |
| --disable-crash-reporter | Disables the crash reporting |
| --disable-default-apps | Disables installation of default apps |
| --disable-domain-reliability | Disables Domain Reliability Monitoring |
| --disable-external-intent-requests | Never forward URL requests to external intents |
| --disable-file-system | Disables FileSystem API |
| --disable-webgl | Disables WebGL |
| --extension-content-verification | Extensions verification |
| --extensions-install-verification | Extensions verification |
| --gpu-rasterization-msaa-sample-count | Numbers of multisample antialiasing samples for GPU rasterization <br> are based on DPI for desktops <br> Android uses 4 by default. Using 0 disables MSAA and improves performance |
| --isolation-by-default | Change several web APIs that make it difficult to isolate origins into distinct processes |
| --js-flags=--jitless | Running V8 in JITless mode enables ACG and CET mitigations in the renderer process, disables WebAssembly and [more](https://v8.dev/blog/jitless). |
| --no-pings | Blocks hyperlink auditing pings |
| --num-raster-threads | Enforces number of worker threads used to rasterize content |
| --process-per-site | Consolidates same-site pages to share a single process |
| --site-per-process | Enforces a one-site-per-process security policy |
| --time-zone-for-testing | Spoofs timzeone |
| --use-fake-device-for-media-stream | Spoofs microphone and camera IDs |
</p></details>

<details><summary>Enabled Features</summary><p>

Partitioning:
* ForceIsolationInfoFrameOriginToTopLevelFrame
* IsolateOrigins
* IsolatePrerenders
* IsolateSandboxedIframes
* OriginIsolationHeader
* PartitionConnectionsByNetworkIsolationKey
* PartitionDomainReliabilityByNetworkIsolationKey
* PartitionExpectCTStateByNetworkIsolationKey
* PartitionHttpServerPropertiesByNetworkIsolationKey
* PartitionNelAndReportingByNetworkIsolationKey
* PartitionSSLSessionsByNetworkIsolationKey
* PartitionedCookies
* SplitAuthCacheByNetworkIsolationKey
* SplitCacheByIncludeCredentials
* SplitCacheByNetworkIsolationKey
* SplitHostCacheByNetworkIsolationKey
* StrictOriginIsolation
	
Sandboxing:
* BrowserDynamicCodeDisabled
	* Prevents the browser process from generating dynamic code or modifying executable code using ACG
* EnableCsrssLockdown
* GpuAppContainer
* NetworkServiceCodeIntegrity
	* Enables CIG mitigation in the network process
* NetworkServiceSandbox
	* Enables ACG mitigation in the network process
* RendererAppContainer
* SandboxExternalProtocolBlocked
* WinSboxDisableExtensionPoint
* WinSboxDisableKtmComponent

Privacy & Security:
* BlockInsecurePrivateNetworkRequests, BlockInsecurePrivateNetworkRequestsForNavigations
	* Blocks insecure private network requests
* ClearCrossSiteCrossBrowsingContextGroupWindowName
* CookieDomainRejectNonASCII
* DisableProcessReuse, ReduceUserAgent
	* The (edge://)flags version are not available on Edge
* EncryptedClientHello
* ImprovedCookieControls
	* Improved third-party cookie blocking/control
* OpaqueResponseBlockingV01
	* [Documentation](https://docs.google.com/document/d/1qUbE2ySi6av3arUEw5DNdFJIKKBbWGRGsXz_ew3S7HQ)
* PostQuantumCECPQ2
* PrefetchPrivacyChanges
	* Prefetch requests will not follow redirects, not send a Referer header, not send credentials for cross-origin requests, and do not pass through service workers
* ReducedReferrerGranularity
	* Enables strict-origin-when-cross-origin

Performance:
* ElementSuperRareData
* IntensiveWakeUpThrottling:grace_period_seconds/10
* ScopeMemoryCachePerContext
* SubframeShutdownDelay
* ThrottleForegroundTimers
* TurnOffStreamingMediaCachingAlways, TurnOffStreamingMediaCachingOnBattery

Others:
* DesktopScreenshots
* RestrictGamepadAccess
* SuppressDifferentOriginSubframeJSDialogs
	* Disallows window.{alert, prompt, confirm} if triggered inside a subframe that is not same origin with the main frame
</p></details>

<details><summary>Disabled Features</summary><p>

Reporting:
* ComputePressure
* ConversionMeasurement
* CrashReporting
* CrostiniAdditionalEnterpriseReporting
* DocumentReporting
* EnableStructuredMetrics
* EnterpriseRealtimeExtensionRequest
* ExpectCTReporting
* Reporting
* SafeBrowsingBetterTelemetryAcrossReports
* TabMetricsLogging

Autofill:
* AutofillEnableAccountWalletStorage
* AutofillServerCommunication

PrivacySandbox/FloC Related:
* AdInterestGroupAPI
* AllowURNsInIframes
* BrowsingTopics
* FedCm
* Fledge
* InterestGroupStorage
* Parakeet

SXG:
* SignedExchangeReportingForDistributors
* SignedHTTPExchange

WebBundles:
* SubresourceWebBundles

ClientHints:
* AcceptCHFrame
* AllowClientHintsToThirdParty
* ClientHintThirdPartyDelegation
* ClientHintsDPR
* ClientHintsDPR_DEPRECATED
* ClientHintsDeviceMemory
* ClientHintsDeviceMemory_DEPRECATED
* ClientHintsMetaHTTPEquivAcceptCH
* ClientHintsMetaNameAcceptCH
* ClientHintsResourceWidth
* ClientHintsResourceWidth_DEPRECATED
* ClientHintsViewportWidth
* ClientHintsViewportWidth_DEPRECATED
* CriticalClientHint
* GreaseUACH
* PrefersColorSchemeClientHintHeader
	* Disabled blocks Dark mode detection via client hints
* UserAgentClientHint
* UserAgentClientHintFullVersionList
* ViewportHeightClientHintHeader

Optimization Hints:
* OptimizationHints
* OptimizationHintsFieldTrials
* OptimizationHintsFetching
* OptimizationHintsFetchingAnonymousDataConsent
* ContextMenuPerformanceInfoAndRemoteHintFetching
* NavigationPredictor

Others:
* AnonymousIframeOriginTrial
* CssSelectorFragmentAnchor
* EnableTLS13EarlyData
* FontAccess
* IdleDetection
	* Blocks Idle Detection
* Journeys
* LensStandalone
* MediaDrmPreprovisioning
	* Blocks DRM (Might break Netflix and Spotify)
* NavigationRequestPreconnect
* NetworkTimeServiceQuerying
	* Disables network time queries in order to prevent Chromium connecting to `clients2.google.com`
* NotificationTriggers
* OmniboxTriggerForNoStatePrefetch
* PreloadMediaEngagementData, MediaEngagementBypassAutoplayPolicies
* Prerender2
* RetailCoupons
* SCTAuditing
* SegmentationPlatform
* SpeculationRulesPrefetchProxy
* TFLiteLanguageDetectionEnabled
* TextFragmentAnchor, CopyLinkToText
	* Disables text snippets in URL fragments
* UsernameFirstFlow, UsernameFirstFlowFilling, UsernameFirstFlowFallbackCrowdsourcing
* WebNFC, WebOTP, WebXR
	* Blocks NFC, OTP and XR APIs
* WebSQLInThirdPartyContextEnabled
* WinrtGeolocationImplementation
	* Blocks Geolocation, you might need to enable it if you are going to use Maps
</p></details>

details><summary>Blink</summary><p>

| Name | Description |
| :--- | :---------- |
| --blink-settings | Sets Blink settings |
| --disable-blink-features | Disables selected Blink features |

blink-settings:
* dnsPrefetchingEnabled = false
	* Disables DNS prefetching
* preferredColorScheme = 1
	* Prevents Dark Mode detection if `#disallow-doc-written-script-loads` is disabled/default
* strictMixedContentChecking, strictMixedContentCheckingForPlugin, strictlyBlockBlockableMixedContent = true
	* Strictly blocks mixed contents

disable-blink-features:
* CrossOriginOpenerPolicyReporting
* DirectSockets
* HandwritingRecognition
* IdleDetection
</p></details>

## Workarounds for common issues.

Remove these lines to fix extensions issues on Ungoogled Chromium
> --extension-content-verification=enforce_strict
> --extensions-install-verification=enforce

#### WebGL / WebGL2

Remove `--disable-webgl`

#### Cannot access any website on Linux & Vivaldi doesn't run & localhost is unreachable

Remove `NetworkServiceSandbox` from `--enable-featues`

#### Slower JavaScript performance & WebAssembly not working

Using JITless mode improves security but might reduce V8’s performance [More Information](https://v8.dev/blog/jitless).

ProtonMail doesn't work in JITLess mode

Remove `--js-flags=--jitless`

#### DevTools, captchas and other third-party frames not working

Remove `--isolation-by-default`

#### Mega.nz

Remove `0x002f` from `--cipher-suite-blacklist`

#### Microphone and camera

Remove `--use-fake-device-for-media-stream`
