# Awesome Vulkan [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<img src="https://github.com/SaschaWillems/Vulkan/blob/master/images/vulkanlogoscene.png" alt="Vulkan demo scene" height="256px">

A curated list of awesome Vulkan libraries, debuggers and resources. Inspired by [awesome-opengl](https://github.com/eug/awesome-opengl) and other awesome-... stuff.

* **[Hardware Support](#hardware-support)**
* **[SDK](#sdk)**
* **[IHV Document](#document)**
* **[Tutorial](#tutorial)**
* **[Apps](#apps)**
* **[Samples](#samples)**
* **[Libraries](#libraries)**
* **[Bindings](#bindings)**
* **[Tools](#tools)**

## Hardware Support
*  [gpuinfo](http://vulkan.gpuinfo.org/) - Vulkan Hardware Database by Sascha Willems
*  [Khronos](https://www.khronos.org/vulkan)
*  [NVIDIA](https://developer.nvidia.com/Vulkan)
 *  [Driver for Desktop](https://developer.nvidia.com/vulkan-driver)
 *  [Driver for Android](https://developer.nvidia.com/vulkan-android)
 *  [Driver for Linux for Tegra (L4T)](https://developer.nvidia.com/embedded/vulkan)
*  [AMD](http://support.amd.com/en-us/kb-articles/Pages/Radeon-Vulkan-Beta.aspx)
*  [Imagination](https://imgtec.com/tools/powervr-early-access-program/)
*  Intel
 *  [Open-source Driver](https://01.org/linuxgraphics/blogs/jekstrand/2016/open-source-vulkan-drivers-intel-hardware/)
 *  [Driver for Windows](https://software.intel.com/en-us/blogs/2016/03/14/new-intel-vulkan-beta-1540204404-graphics-driver-for-windows-78110-1540)
*  [Qualcomm](https://developer.qualcomm.com/software/adreno-gpu-sdk/gpu)
*  [ARM](http://malideveloper.arm.com/resources/sdks/mali-vulkan-sdk/)

## SDK
*  [For Windows & Linux](https://vulkan.lunarg.com/signin)
*  [For Android](https://developer.android.com/ndk/guides/graphics/index.html)

## Document
*  [AMD](http://gpuopen.com/gaming-product/vulkan/)
  *   [Vulkan Fast Paths](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/VulkanFastPaths.pdf)
  *   [Let Your Game Shine – Optimizing DirectX 12 and Vulkan Performance with AMD CodeXL	](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/Let_your_game_shine_optimizing_DirectX-12_and_Vulkan-performance_with_AMD_CodeXL.pdf)
  *   [D3D12 & Vulkan: Lessons Learned	 ](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/d3d12_vulkan_lessons_learned.pdf)
  *  [Say Hello to a New Rendering API in Town!](http://gpuopen.com/say-hello/)
  *  [Vulkan Renderpasses](http://gpuopen.com/vulkan-renderpasses/)
  *  [Performance tweets series: Barriers, fences, synchronization](http://gpuopen.com/performance-tweets-series-barriers-fences-synchronization/)
  *  [Using the Vulkan™ Validation Layers](http://gpuopen.com/using-the-vulkan-validation-layers/)
  *  [Most common mistakes in Vulkan apps](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/05/Most-common-mistakes-in-Vulkan-apps.pdf)
*  [NVIDIA](https://developer.nvidia.com/taxonomy/term/586)
  * [GPU-Driven Rendering](http://on-demand.gputechconf.com/gtc/2016/presentation/s6138-christoph-kubisch-pierre-boudier-gpu-driven-rendering.pdf) 
  * [GDC 16 - High-performance, Low-Overhead Rendering with OpenGL and Vulkan](http://developer.download.nvidia.com/gameworks/events/GDC2016/mschott_lbishop_gl_vulkan.pdf)  
  * [GDC 16 - Vulkan and NVIDIA – The Essentials](http://developer.download.nvidia.com/gameworks/events/GDC2016/Vulkan_Essentials_GDC16_tlorach.pdf)
  * [Engaging the Voyage to Vulkan](https://developer.nvidia.com/engaging-voyage-vulkan)
  * [Vulkan Shader Resource Binding](https://developer.nvidia.com/vulkan-shader-resource-binding)
  * [Vulkan Memory Management](https://developer.nvidia.com/vulkan-memory-management)
  * [OpenGL like Vulkan](https://developer.nvidia.com/opengl-vulkan)
  * [Transitioning from OpenGL to Vulkan](https://developer.nvidia.com/transitioning-opengl-vulkan)
  * [Siggraph 15 talk - Vulkan on NVIDIA GPUs](http://on-demand.gputechconf.com/siggraph/2015/presentation/SIG1501-Piers-Daniell.pdf)
*  ARM
  * [Porting a Graphics Engine to the Vulkan API](https://community.arm.com/groups/arm-mali-graphics/blog/2016/02/16/porting-a-graphics-engine-to-the-vulkan-api)
  * [Multi-Threading in Vulkan](https://community.arm.com/groups/arm-mali-graphics/blog/2016/04/19/massively-multi-thread-for-vulkan)
  * [Vulkan's Key Features on ARM Architecture](http://malideveloper.arm.com/downloads/Presentations/GDC%202016/Theatre/Vulkan%20API%20key%20features%20on%20ARM%20architecture.pdf)
  * [Get Your Engine Ready for Vulkan on Mobile](http://malideveloper.arm.com/downloads/Presentations/GDC%202016/Theatre/Get%20Your%20Engine%20Ready%20for%20Vulkan%20on%20Mobile.pdf)
  * [Mali Vulkan Tutorials](http://malideveloper.arm.com/downloads/deved/tutorial/SDK/Vulkan/1.0/tutorials.html) - Basic Vulkan tutorials from the [Mali Vulkan SDK](http://malideveloper.arm.com/resources/sdks/mali-vulkan-sdk/)
* Intel
  * [API without Secrets: Introduction to Vulkan](https://github.com/GameTechDev/IntroductionToVulkan) [[LICENSE](https://github.com/GameTechDev/IntroductionToVulkan/blob/master/license.txt)]
    * [Part 1: The Beginning](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-1)
    * [Part 2: Swap Chain](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-2)
    * [Part 3: First Triangle](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-3)
* [Imagination](http://blog.imgtec.com/tag/vulkan)
  * [Efficient Rendering with Vulkan on PowerVR](https://imagination-technologies-cloudfront-assets.s3.amazonaws.com/idc-docs/gdc16/6_Efficient%20rendering%20with%20Vulkan%20on%20PowerVR.pdf)
  *  [Migrating to Vulkan with the New PowerVR Graphics Framework](https://imagination-technologies-cloudfront-assets.s3.amazonaws.com/idc-docs/gdc16/7_FrameworkIDC16.pdf)
* Samgsung
  * [Siggraph 2016 - Best Practices for Mobile](https://community.arm.com/servlet/JiveServlet/download/96891546-24708/6-mmg-siggraph2016-vulkan-smedis.pdf)
* Epic
  * [Efficient use of Vulkan on UE4 Mobile](https://community.arm.com/servlet/JiveServlet/download/96891546-24708/6-mmg-siggraph2016-vulkan-smedis.pdf)

## Tutorial
*  [jhenriques's tutorial](http://av.dfki.de/~jhenriques/development.html)
*  [Khronos](https://www.khronos.org/registry/vulkan/)
 *  [Vulkan 1.0 Quick Reference](https://www.khronos.org/registry/vulkan/specs/1.0/refguide/Vulkan-1.0-web.pdf)
 *  [Vulkan 1.0 Specification](https://www.khronos.org/registry/vulkan/specs/1.0-wsi_extensions/pdf/vkspec.pdf)
 *  [GDC 2016 Presentations](https://www.khronos.org/developers/library/2016-gdc)
 *  [Moving to Vulkan Khronos UK May16](https://www.khronos.org/assets/uploads/developers/library/2016-uk-chapter-moving-to-vulkan/Moving-to-Vulkan_Khronos-UK_May16.pdf)
 *  [SIGGRPAH 2016 3D BOF](https://www.khronos.org/assets/uploads/developers/library/2016-siggraph/Khronos-3D-BOF-SIGGRAPH_Jul16.pdf)
*  [Vulkan Programming Guide](http://www.amazon.com/Vulkan-Programming-Guide-Official-Learning/dp/0134464540) - AKA the Red Book.
* Siggraph
  * [An overview of next-generation graphics APIs](http://nextgenapis.realtimerendering.com/) - covers Vulkan, D3D12 etc.
*  [vulkan-sxs](https://github.com/philiptaylor/vulkan-sxs) - explain the Vulkan API step by step and [vulkan-sync] (https://github.com/philiptaylor/vulkan-sync) - rephrase Vulkan's requirements on execution dependencies in a more precise form. [MIT]
*  [Vulkan in 30 minutes](https://renderdoc.org/vulkan-in-30-minutes.html) - by baldurk.
*  [Tutorial by Overv](https://vulkan-tutorial.com/) and [its github repository](https://github.com/Overv/VulkanTutorial). [CC BY-SA 4.0]

## Apps
*  [The Talos Principle](http://www.croteam.com/talos-principle-will-support-vulkan-first-screenshot-released/) - by Croteam.
*  [Dota2](https://github.com/ValveSoftware/Dota-2-Vulkan/) - by Valve.
*  [Basemark](http://www.basemark.com/2015/11/10/basemark-extends-its-benchmarking-lead-with-a-vulkan-performance-test/) - by Basemark.
*  [GFXBench 5](https://kishonti.net/news_single.jsp?id=31133884) - by Kishonti.
*  [ProtoStar](https://www.unrealengine.com/blog/epic-games-unveils-protostar-at-samsung-galaxy-unpacked) - by Epic, built with Unreal Engine 4 technology.
*  [Doom](https://en.wikipedia.org/wiki/Doom_(2016_video_game)) - by id Software.

## Samples
*  Sascha Willems's [samples](https://github.com/SaschaWillems/Vulkan) and [Deferred rendering of  Sponza](https://github.com/SaschaWillems/VulkanSponza) and his talk of [Khronos_meetup_munich](https://github.com/SaschaWillems/Vulkan/blob/master/documentation/Khronos_meetup_munich_fromGLtoVulkan.pdf).
*  McNopper's [examples](https://github.com/McNopper/Vulkan)
*  [KhronosGroup](https://github.com/KhronosGroup)
 *  [Samples](https://github.com/KhronosGroup/Vulkan-Samples)
 *  [Conformance Tests (CTS)](https://github.com/KhronosGroup/Vulkan-CTS)
*  Google
 *  [Android port of LunarG samples](https://github.com/googlesamples/vulkan-basic-samples).
 *  [android tutorials](https://github.com/googlesamples/android-vulkan-tutorials).
*  [nvpro-samples](https://github.com/nvpro-samples) - NVIDIA DesignWorks Samples. [[LICENSE](https://github.com/nvpro-samples/gl_vk_threaded_cadscene/blob/master/LICENSE)]
 *  [gl_vk_chopper](https://github.com/nvpro-samples/gl_vk_chopper) - Simple vulkan rendering example.
 *  [gl_vk_threaded_cadscene](https://github.com/nvpro-samples/gl_vk_threaded_cadscene) - OpenGL and Vulkan comparison on rendering a CAD scene using veraious techniques and [the blog](https://developer.nvidia.com/vulkan-opengl-threaded-cad-scene-sample) about it.
 *  [gl_vk_bk3dthreaded](https://github.com/nvpro-samples/gl_vk_bk3dthreaded) - Vulkan sample rendering 3D with 'worker-threads'.
 *  [gl_vk_supersampled](https://github.com/nvpro-samples/gl_vk_supersampled) - Vulkan sample showing a high quality super-sampled rendering.
*  [NVIDIA GameWorks Samples](https://github.com/NVIDIAGameWorks/GraphicsSamples) - GameWorks cross-platform graphics API samples. [[LICENSE](https://github.com/NVIDIAGameWorks/GraphicsSamples/blob/master/license.txt)]
*  [LunarG's samples](https://github.com/LunarG/VulkanSamples)
*  [vkcube](https://github.com/krh/vkcube) - 'vkcube' sample from krh, works under X, wayland and VT console with
drm/kms.
*  [Stardust from Intel](https://github.com/GameTechDev/stardust_vulkan) - The Stardust sample application uses the Vulkan graphics API to efficiently render a cloud of animated particles. [[LICENSE](https://github.com/GameTechDev/stardust_vulkan/blob/master/license.txt)]
*  [Introductory Vulkan sample from AMD](https://github.com/GPUOpen-LibrariesAndSDKs/HelloVulkan). [MIT]
*  [Vulkan Quake port based on QuakeSpasm](https://github.com/Novum/vkQuake).

## Libraries
*  [Cinder](https://github.com/cinder/Cinder) and [the story](https://libcinder.org/notes/vulkan) [behind](https://forum.libcinder.org/#Topic/23286000002614007). [BSD]
*  [openFrameworks](https://github.com/openframeworks-vk/openFrameworks) - the most famouse C++ creative coding framework. [MIT]
*  [bgfx](https://github.com/bkaradzic/bgfx) - Cross-platform rendering library, bgfx backend is WIP. [[LICENSE](https://github.com/bkaradzic/bgfx/blob/master/LICENSE)]
*  [PowerVR SDK](https://github.com/powervr-graphics/Native_SDK) - C++ cross-platform 3D graphics SDK to speed up development of Vulkan and GLES. [[LICENSE](https://github.com/powervr-graphics/Native_SDK/blob/4.1/LICENSE_POWERVR_SDK.txt)]
*  [glfw](https://github.com/glfw/glfw) and [the guide](http://www.glfw.org/docs/3.2/vulkan.html).  [[LICENSE](https://github.com/glfw/glfw/blob/master/COPYING.txt)]
*  [MetalVK](https://moltengl.com/metalvk/) - run Vulkan on iOS and OS X. [Non-free]
*  [imgui](https://github.com/ocornut/imgui) - Immediate Mode Graphical User interface. [MIT]
*  [libvc](https://github.com/alexhultman/libvc) - Vulkan Compute for C++.  [[LICENSE](https://github.com/alexhultman/libvc/blob/master/LICENSE)]
*  [AMD's Anvil](https://github.com/GPUOpen-LibrariesAndSDKs/Anvil) - cross-platform framework for Vulkan. [[LICENSE](https://github.com/GPUOpen-LibrariesAndSDKs/OutOfOrderRasterization/blob/master/LICENSE.txt)]
*  [Google's vulkan-cpp-library](https://github.com/google/vulkan-cpp-library) - Vulkan abstraction library using C++11 for memory, resource management, type and thread safety as well as system independency. [Apache]
*  [Vookoo](https://github.com/andy-thomason/Vookoo) - Vulkan Utititles Library. [MIT]
*  [vpp](https://github.com/nyorain/vpp) - Modern C++ Vulkan Abstraction focused on performance and a straightforward interface. [MIT]

## Bindings
*  [libvulkan.lua](https://github.com/CapsAdmin/ffibuild/blob/master/examples/vulkan/libvulkan.lua) - Lua bindings for Vulkan.
*  [dvulkan](https://github.com/ColonelThirtyTwo/dvulkan) - Auto-generated D bindings for Vulkan.
*  [ErupteD](https://github.com/ParticlePeter/ErupteD) - Another Auto-generated D bindings for Vulkan.
*  [Haskell bindings for Vulkan](https://github.com/expipiplus1/vulkan) - [[LICENSE](https://github.com/expipiplus1/vulkan/blob/master/LICENSE)]
*  [Vulkan-hpp](https://github.com/KhronosGroup/Vulkan-Hpp) Open-Source Vulkan C++ API originated from NVIDIA and [the blog](https://developer.nvidia.com/open-source-vulkan-c-api) about it.
*  [VulkanSharp](https://github.com/mono/VulkanSharp) - C# bindings for Vulkan. [MIT]
*  [Vulkano](https://github.com/tomaka/vulkano) - Safe and rich Rust wrapper around the Vulkan API. [MIT]
*  [LWJGL](https://www.lwjgl.org/) - Lightweight Java Game Library 3 has Vulkan bindings. [BSD]
  
## Tools
*  [Nsight™ Visual Studio Edition 5.2+](https://developer.nvidia.com/nvidia-nsight-visual-studio-edition).
*  [LoaderAndValidationLayers](https://github.com/KhronosGroup/Vulkan-LoaderAndValidationLayers) - from KhronosGroup. [MIT]
*  [renderdoc](https://github.com/baldurk/renderdoc) - by baldurk, a stand-alone graphics debugging tool. [MIT]
*  [VulkanTools](https://github.com/LunarG/VulkanTools) - LunarG's tools including layers, `vktrace` and `vkreplay`. [MIT]
*  [CodeXL](https://github.com/GPUOpen-Tools/CodeXL) - CodeXL goes open source. [MIT]
*  [Qualcomm GPU Tools](https://developer.qualcomm.com/software/adreno-gpu-sdk/tools).
*  [Mali Graphics Debugger](http://malideveloper.arm.com/resources/tools/mali-graphics-debugger/).

## Related lists

*Similar awesome lists*
* [awesome](https://github.com/sindresorhus/awesome) - A curated list of awesome lists.
* [awesome-opengl](https://github.com/eug/awesome-opengl) - A curated list of awesome OpenGL libraries, debuggers and resources.
* [gamedev](https://github.com/ellisonleao/magictools) - A awesome list about game development.
* [graphics-resources](https://github.com/mattdesl/graphics-resources) - A list of graphic programming resources.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## Contributing
Please see [CONTRIBUTING](https://github.com/vinjn/awesome-vulkan/blob/master/CONTRIBUTING.md) for details.
