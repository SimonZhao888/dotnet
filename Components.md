﻿# List of components

To enable full offline source-building of the VMR, we have no other choice than to synchronize all the necessary code into the VMR. This also includes any code referenced via git submodules. More details on why and how this is done can be found here:
- [Strategy for managing external source dependencies](src/arcade/Documentation/UnifiedBuild/VMR-Strategy-For-External-Source.md)
- [Source Synchronization Process](src/arcade/Documentation/UnifiedBuild/VMR-Design-And-Operation.md#source-synchronization-process)

## Detailed list

<!-- component list beginning -->
- `src/arcade`  
*[dotnet/arcade@1c7e09a](https://github.com/dotnet/arcade/tree/1c7e09a8d9c9c9b15ba574cd6a496553505559de)*
- `src/aspire`  
*[dotnet/aspire@5fa9337](https://github.com/dotnet/aspire/tree/5fa9337a84a52e9bd185d04d156eccbdcf592f74)*
- `src/aspnetcore`  
*[_git/dotnet-aspnetcore@af22eff](https://dev.azure.com/dnceng/internal/_git/dotnet-aspnetcore/?version=GCaf22effae4069a5dfb9b0735859de48820104f5b)*
    - `src/aspnetcore/src/submodules/googletest`  
    *[google/googletest@6dae7eb](https://github.com/google/googletest/tree/6dae7eb4a5c3a169f3e298392bff4680224aa94a)*
    - `src/aspnetcore/src/submodules/MessagePack-CSharp`  
    *[aspnet/MessagePack-CSharp@9aeb12b](https://github.com/aspnet/MessagePack-CSharp/tree/9aeb12b9bdb024512ffe2e4bddfa2785dca6e39e)*
- `src/cecil`  
*[dotnet/cecil@e51bd36](https://github.com/dotnet/cecil/tree/e51bd3677d5674fa34bf5676c5fc5562206bf94e)*
- `src/command-line-api`  
*[dotnet/command-line-api@803d859](https://github.com/dotnet/command-line-api/tree/803d8598f98fb4efd94604b32627ee9407f246db)*
- `src/deployment-tools`  
*[dotnet/deployment-tools@7871ee3](https://github.com/dotnet/deployment-tools/tree/7871ee378dce87b64d930d4f33dca9c888f4034d)*
- `src/diagnostics`  
*[dotnet/diagnostics@513150c](https://github.com/dotnet/diagnostics/tree/513150c2f25077b1fcb194407e53c433c975f39b)*
- `src/efcore`  
*[_git/dotnet-efcore@645f313](https://dev.azure.com/dnceng/internal/_git/dotnet-efcore/?version=GC645f3131a5b0a4bf677201cf22773990a5316c89)*
- `src/emsdk`  
*[dotnet/emsdk@763d10a](https://github.com/dotnet/emsdk/tree/763d10a1a251be35337ee736832bfde3f9200672)*
- `src/fsharp`  
*[dotnet/fsharp@f07a914](https://github.com/dotnet/fsharp/tree/f07a91420bec3f657153e16c9f047cf151c1179f)*
- `src/msbuild`  
*[dotnet/msbuild@1cce779](https://github.com/dotnet/msbuild/tree/1cce77968bca1366760f361c837ffbc3a6af70f0)*
- `src/nuget-client`  
*[nuget/nuget.client@aa7eb99](https://github.com/nuget/nuget.client/tree/aa7eb9987d28e7169cfabfa484f2fdd22d2b91d2)*
    - `src/nuget-client/submodules/NuGet.Build.Localization`  
    *[NuGet/NuGet.Build.Localization@f15db7b](https://github.com/NuGet/NuGet.Build.Localization/tree/f15db7b7c6f5affbea268632ef8333d2687c8031)*
- `src/razor`  
*[dotnet/razor@88f8675](https://github.com/dotnet/razor/tree/88f8675df43ec706bb4089bd5f91d0a5dbbd3f94)*
- `src/roslyn`  
*[dotnet/roslyn@913fb4e](https://github.com/dotnet/roslyn/tree/913fb4ecf8382b79d29e8a4434bb5667f7988846)*
- `src/roslyn-analyzers`  
*[dotnet/roslyn-analyzers@3d61c57](https://github.com/dotnet/roslyn-analyzers/tree/3d61c57c73c3dd5f1f407ef9cd3414d94bf0eaf2)*
- `src/runtime`  
*[_git/dotnet-runtime@9d5a6a9](https://dev.azure.com/dnceng/internal/_git/dotnet-runtime/?version=GC9d5a6a9aa463d6d10b0b0ba6d5982cc82f363dc3)*
- `src/scenario-tests`  
*[dotnet/scenario-tests@1009e3b](https://github.com/dotnet/scenario-tests/tree/1009e3b6d23e049de56b91de82fe975fe84444f8)*
- `src/sdk`  
*[dotnet/sdk@c1130ce](https://github.com/dotnet/sdk/tree/c1130ce1786404c71d0e6d834a8356590830db5f)*
- `src/source-build-externals`  
*[dotnet/source-build-externals@c65b1c1](https://github.com/dotnet/source-build-externals/tree/c65b1c1affed1f4847f9c3f81623dfa929d21e1a)*
    - `src/source-build-externals/src/abstractions-xunit`  
    *[xunit/abstractions.xunit@b75d54d](https://github.com/xunit/abstractions.xunit/tree/b75d54d73b141709f805c2001b16f3dd4d71539d)*
    - `src/source-build-externals/src/application-insights`  
    *[microsoft/ApplicationInsights-dotnet@43825e0](https://github.com/microsoft/ApplicationInsights-dotnet/tree/43825e06a22cdfb702fc199a7ba99a7d541d48c6)*
    - `src/source-build-externals/src/azure-activedirectory-identitymodel-extensions-for-dotnet`  
    *[AzureAD/azure-activedirectory-identitymodel-extensions-for-dotnet@e67b25b](https://github.com/AzureAD/azure-activedirectory-identitymodel-extensions-for-dotnet/tree/e67b25be77532af9ba405670b34b4d263d505fde)*
    - `src/source-build-externals/src/cssparser`  
    *[dotnet/cssparser@0d59611](https://github.com/dotnet/cssparser/tree/0d59611784841735a7778a67aa6e9d8d000c861f)*
    - `src/source-build-externals/src/docker-creds-provider`  
    *[mthalman/docker-creds-provider@6c73fa4](https://github.com/mthalman/docker-creds-provider/tree/6c73fa4784795ae07f49305a057abf5c473d2adb)*
    - `src/source-build-externals/src/humanizer`  
    *[Humanizr/Humanizer@3ebc38d](https://github.com/Humanizr/Humanizer/tree/3ebc38de585fc641a04b0e78ed69468453b0f8a1)*
    - `src/source-build-externals/src/MSBuildLocator`  
    *[microsoft/MSBuildLocator@e0281df](https://github.com/microsoft/MSBuildLocator/tree/e0281df33274ac3c3e22acc9b07dcb4b31d57dc0)*
    - `src/source-build-externals/src/newtonsoft-json`  
    *[JamesNK/Newtonsoft.Json@0a2e291](https://github.com/JamesNK/Newtonsoft.Json/tree/0a2e291c0d9c0c7675d445703e51750363a549ef)*
    - `src/source-build-externals/src/spectre-console`  
    *[spectreconsole/spectre.console@7397169](https://github.com/spectreconsole/spectre.console/tree/7397169a2757dc3657598bdea4ac222c0f283425)*
    - `src/source-build-externals/src/xunit`  
    *[xunit/xunit@f110e5b](https://github.com/xunit/xunit/tree/f110e5bee5dfd4c08339587c9c3df9292fcb597c)*
    - `src/source-build-externals/src/xunit/src/xunit.assert/Asserts`  
    *[xunit/assert.xunit@5c8c10e](https://github.com/xunit/assert.xunit/tree/5c8c10e085eb42f39f2fe0b40c94bf56649eb0a4)*
    - `src/source-build-externals/src/xunit/tools/build`  
    *[xunit/build-tools@8e186b0](https://github.com/xunit/build-tools/tree/8e186b0f8e398796e75453f3f18952b06d29fdfd)*
    - `src/source-build-externals/src/xunit/tools/media`  
    *[xunit/media@5738b6e](https://github.com/xunit/media/tree/5738b6e86f08e0389c4392b939c20e3eca2d9822)*
- `src/source-build-reference-packages`  
*[dotnet/source-build-reference-packages@a3776f6](https://github.com/dotnet/source-build-reference-packages/tree/a3776f67d97bd5d9ada92122330454b284bfe915)*
- `src/sourcelink`  
*[dotnet/sourcelink@a190fdd](https://github.com/dotnet/sourcelink/tree/a190fddd4aeb983b59b682c984692639c8c7d100)*
- `src/symreader`  
*[dotnet/symreader@0710a78](https://github.com/dotnet/symreader/tree/0710a7892d89999956e8808c28e9dd0512bd53f3)*
- `src/templating`  
*[dotnet/templating@e660cd9](https://github.com/dotnet/templating/tree/e660cd905cc907f7167c0826e2c30eb57a87e4da)*
- `src/test-templates`  
*[dotnet/test-templates@2adf582](https://github.com/dotnet/test-templates/tree/2adf5822dc94d97d0f6e1584129fcf65ba837097)*
- `src/vstest`  
*[microsoft/vstest@bc91613](https://github.com/microsoft/vstest/tree/bc9161306b23641b0364b8f93d546da4d48da1eb)*
- `src/windowsdesktop`  
*[_git/dotnet-windowsdesktop@308dc79](https://dev.azure.com/dnceng/internal/_git/dotnet-windowsdesktop/?version=GC308dc7955704be60afc72ec00902cc18e028c3c2)*
- `src/winforms`  
*[_git/dotnet-winforms@62ebdb4](https://dev.azure.com/dnceng/internal/_git/dotnet-winforms/?version=GC62ebdb4b0d5cc7e163b8dc9331dc196e576bf162)*
- `src/wpf`  
*[_git/dotnet-wpf@a04736a](https://dev.azure.com/dnceng/internal/_git/dotnet-wpf/?version=GCa04736acb8edb533756131d3d5fc55f15cd03d6a)*
- `src/xdt`  
*[dotnet/xdt@1a54480](https://github.com/dotnet/xdt/tree/1a54480f52703fb45fac2a6b955247d33758383e)*
- `src/xliff-tasks`  
*[dotnet/xliff-tasks@73f0850](https://github.com/dotnet/xliff-tasks/tree/73f0850939d96131c28cf6ea6ee5aacb4da0083a)*
<!-- component list end -->

The repository also contains a [JSON manifest](https://github.com/dotnet/dotnet/blob/main/src/source-manifest.json) listing all components in a machine-readable format.
