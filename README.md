# Awesome Vulkan [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<img src="https://raw.githubusercontent.com/SaschaWillems/Vulkan/master/images/vulkanlogoscene.png" alt="Vulkan demo scene" height="256px">

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
* **[Books](#books)**
* **[Khronos](#khronos)**
* **[Community](#community)**

## Hardware Support
*  [gpuinfo](http://vulkan.gpuinfo.org/) - Vulkan Hardware Database by Sascha Willems
*  [Khronos](https://www.khronos.org/vulkan)
*  [NVIDIA](https://developer.nvidia.com/Vulkan)
    *  [Driver for Desktop](https://developer.nvidia.com/vulkan-driver)
    *  [Driver for Android](https://developer.nvidia.com/vulkan-android)
    *  [Driver for Linux for Tegra (L4T)](https://developer.nvidia.com/embedded/vulkan)
*  [AMD](http://www.amd.com/en-gb/innovations/software-technologies/technologies-gaming/vulkan)
    *  [Open-source Driver](https://github.com/GPUOpen-Drivers/AMDVLK)
*  [Imagination](https://www.imgtec.com/developers/powervr-sdk-tools/)
*  Intel
    *  [Open-source Driver](https://01.org/linuxgraphics/blogs/jekstrand/2016/open-source-vulkan-drivers-intel-hardware/)
    *  [Driver for Windows](https://software.intel.com/en-us/blogs/2016/03/14/new-intel-vulkan-beta-1540204404-graphics-driver-for-windows-78110-1540)
*  [Qualcomm](https://developer.qualcomm.com/software/adreno-gpu-sdk/gpu)
*  Arm
    *  [Mali GPU Best Practices](https://developer.arm.com/solutions/graphics/developer-guides/mali-gpu-best-practices)

## SDK
*  [For Windows & Linux](https://vulkan.lunarg.com/signin)
*  [For Android](https://developer.android.com/ndk/guides/graphics/index.html)

## Document
*  [AMD](http://gpuopen.com/tag/vulkan/)
    *  [Vulkan barriers explained](http://gpuopen.com/vulkan-barriers-explained/)
    *  [Vulkan Fast Paths](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/VulkanFastPaths.pdf)
    *  [Let Your Game Shine – Optimizing DirectX 12 and Vulkan Performance with AMD CodeXL	](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/Let_your_game_shine_optimizing_DirectX-12_and_Vulkan-performance_with_AMD_CodeXL.pdf)
    *  [D3D12 & Vulkan: Lessons Learned	 ](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/03/d3d12_vulkan_lessons_learned.pdf)
    *  [Say Hello to a New Rendering API in Town!](http://gpuopen.com/say-hello/)
    *  [Vulkan Renderpasses](http://gpuopen.com/vulkan-renderpasses/)
    *  [Performance tweets series: Barriers, fences, synchronization](http://gpuopen.com/performance-tweets-series-barriers-fences-synchronization/)
    *  [Using the Vulkan™ Validation Layers](http://gpuopen.com/using-the-vulkan-validation-layers/)
    *  [Most common mistakes in Vulkan apps](http://32ipi028l5q82yhj72224m8j.wpengine.netdna-cdn.com/wp-content/uploads/2016/05/Most-common-mistakes-in-Vulkan-apps.pdf)
	*  [Vulkan Device Memory](http://gpuopen.com/vulkan-device-memory/)
*  [NVIDIA](https://developer.nvidia.com/taxonomy/term/586)
    * [Vulkan Device-Generated Commands](https://developer.nvidia.com/device-generated-commands-vulkan)
    * [Getting Vulkan Ready For VR](https://developer.nvidia.com/getting-vulkan-ready-vr)
    * [GPU-Driven Rendering](http://on-demand.gputechconf.com/gtc/2016/presentation/s6138-christoph-kubisch-pierre-boudier-gpu-driven-rendering.pdf)
    * [GDC 16 - High-performance, Low-Overhead Rendering with OpenGL and Vulkan](http://developer.download.nvidia.com/gameworks/events/GDC2016/mschott_lbishop_gl_vulkan.pdf)
    * [GDC 16 - Vulkan and NVIDIA – The Essentials](http://developer.download.nvidia.com/gameworks/events/GDC2016/Vulkan_Essentials_GDC16_tlorach.pdf)
    * [Engaging the Voyage to Vulkan](https://developer.nvidia.com/engaging-voyage-vulkan)
    * [Vulkan Shader Resource Binding](https://developer.nvidia.com/vulkan-shader-resource-binding)
    * [Vulkan Memory Management](https://developer.nvidia.com/vulkan-memory-management)
    * [OpenGL like Vulkan](https://developer.nvidia.com/opengl-vulkan)
    * [Transitioning from OpenGL to Vulkan](https://developer.nvidia.com/transitioning-opengl-vulkan)
    * [Siggraph 15 talk - Vulkan on NVIDIA GPUs](http://on-demand.gputechconf.com/siggraph/2015/presentation/SIG1501-Piers-Daniell.pdf)
*  [Arm](https://developer.arm.com/solutions/graphics/apis/vulkan)
    * [Vulkan Best Practice for Mobile Developers Tutorials](https://github.com/ARM-software/vulkan_best_practice_for_mobile_developers)
    * [Vulkan's Key Features on Arm Architecture](https://developer.arm.com/-/media/Files/pdf/graphics-and-multimedia/Vulkan%20API%20key%20features%20on%20ARM%20architecture.pdf)
    * [Porting a Graphics Engine to the Vulkan API](https://community.arm.com/groups/arm-mali-graphics/blog/2016/02/16/porting-a-graphics-engine-to-the-vulkan-api)
    * [Get Your Engine Ready for Vulkan on Mobile](https://developer.arm.com/-/media/Files/pdf/graphics-and-multimedia/Get%20Your%20Engine%20Ready%20for%20Vulkan%20on%20Mobile.pdf)
    * [Multi-Threading in Vulkan](https://community.arm.com/groups/arm-mali-graphics/blog/2016/04/19/massively-multi-thread-for-vulkan)
    * [Mali Vulkan SDK Tutorials](https://developer.arm.com/products/software/mali-sdks/vulkan) and [Slides](https://developer.arm.com/graphics/vulkan/vulkan-tutorials)
* Intel
    * [API without Secrets: Introduction to Vulkan](https://github.com/GameTechDev/IntroductionToVulkan) [[LICENSE](https://github.com/GameTechDev/IntroductionToVulkan/blob/master/license.txt)]
        * [Part 1: The Beginning](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-1)
        * [Part 2: Swap Chain](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-2)
        * [Part 3: First Triangle](https://software.intel.com/en-us/api-without-secrets-introduction-to-vulkan-part-3)
        * [Part 4: Vertex Attributes](https://software.intel.com/en-us/articles/api-without-secrets-introduction-to-vulkan-part-4)
* [Imagination](http://blog.imgtec.com/tag/vulkan)
    * [Efficient Rendering with Vulkan on PowerVR](https://imagination-technologies-cloudfront-assets.s3.amazonaws.com/idc-docs/gdc16/6_Efficient%20rendering%20with%20Vulkan%20on%20PowerVR.pdf)
    * [Migrating to Vulkan with the New PowerVR Graphics Framework](https://www.imgtec.com/webinar/migrating-to-vulkan-with-the-powervr-framework/)
    * [Migrating from OpenGLES to Vulkan](https://www.imgtec.com/downloads/download-info/migrating-from-opengl-es-to-vulkan/)
* Samsung
    * [Siggraph 2016 - Best Practices for Mobile](https://community.arm.com/cfs-file/__key/telligent-evolution-extensions-calendar-calendarfiles/00-00-00-00-05/2_2D00_mmg_2D00_siggraph2016_2D00_best_2D00_practice_2D00_andrew.pdf)
    * [Vulkan Usage Recommencation](https://developer.samsung.com/game/usage) (for mobile)
* Epic
    * [Efficient use of Vulkan on UE4 Mobile](https://community.arm.com/cfs-file/__key/telligent-evolution-extensions-calendar-calendarfiles/00-00-00-00-05/6_2D00_mmg_2D00_siggraph2016_2D00_vulkan_2D00_smedis.pdf)
*  Khronos
   * [Vulkan Guide](https://github.com/KhronosGroup/Vulkan-Guide)    

## Tutorial
*  [How to Learn Vulkan](https://www.jeremyong.com/c++/vulkan/graphics/rendering/2018/03/26/how-to-learn-vulkan.html) - Meta post on how to learn Vulkan
*  [I Am Graphics And So Can You](https://www.fasterthan.life/blog/2017/7/11/i-am-graphics-and-so-can-you-part-1) - Blog post style tutorial for those new to graphics learning Vulkan.
*  [Moving to Vulkan (Khronos UK May16)](https://www.khronos.org/assets/uploads/developers/library/2016-uk-chapter-moving-to-vulkan/Moving-to-Vulkan_Khronos-UK_May16.pdf)
*  [jhenriques's tutorial](http://jhenriques.net/development.html)
*  [Lunarg's tutorial](https://vulkan.lunarg.com/doc/sdk/1.0.26.0/windows/tutorial.html)
*  [Mike Bailey's Vulkan Page](http://web.engr.oregonstate.edu/~mjb/vulkan/) - Provides extensive Vulkan course slides. [CC BY-NC-ND 4.0]
*  [Qualcomm Video Tutorial Series](https://developer.qualcomm.com/software/adreno-gpu-sdk/tutorial-videos) - Leans more towards Vulkan for mobile devices.
*  [Raw Vulkan](https://alain.xyz/blog/raw-vulkan) - Overview on how to program a Vulkan application from the ground up.
* Siggraph
    * [An overview of next-generation graphics APIs](http://nextgenapis.realtimerendering.com/) - covers Vulkan, D3D12 etc.
*  [Tutorial by Overv](https://vulkan-tutorial.com/) and [its github repository](https://github.com/Overv/VulkanTutorial). [CC BY-SA 4.0]
*  [vulkan-sxs](https://github.com/philiptaylor/vulkan-sxs) - explain the Vulkan API step by step and [vulkan-sync](https://github.com/philiptaylor/vulkan-sync) - rephrase Vulkan's requirements on execution dependencies in a more precise form. [MIT]
*  [Vulkan in 30 minutes](https://renderdoc.org/vulkan-in-30-minutes.html) - by baldurk.
*  [Vulkan Demos and Tutorials](https://github.com/Z80Fan/VulkanDemos). [MIT]

## Apps
*  [The Talos Principle](http://www.croteam.com/talos-principle-will-support-vulkan-first-screenshot-released/) - by Croteam.
*  [Dota2](https://github.com/ValveSoftware/Dota-2-Vulkan/) - by Valve.
*  [Basemark](https://www.basemark.com/blog/basemark-extends-its-benchmarking-lead-with-a-vulkan-performance-test/) - by Basemark.
*  [GFXBench 5](https://kishonti.net/news_single.jsp?id=31133884) - by Kishonti.
*  [ProtoStar](https://www.unrealengine.com/blog/epic-games-unveils-protostar-at-samsung-galaxy-unpacked) - by Epic, built with Unreal Engine 4 technology.
*  [Doom](https://en.wikipedia.org/wiki/Doom_(2016_video_game)) - by id Software.
*  [vkQuake](https://github.com/Novum/vkQuake) - Vulkan Quake port based on QuakeSpasm. [GPL]
*  [vkQuake2](https://github.com/kondrak/vkQuake2) - id Software's Quake 2 v3.21 with Vulkan support (Windows and Linux). [GPL]
*  [q2vkpt](https://github.com/cschied/q2vkpt/) - Real-time path tracer VKPT integrated into q2pro Quake 2 client. [gpl]
*  [Linux port of SteamVR](https://github.com/ValveSoftware/SteamVR-for-Linux) - SteamVR is built on top of the Vulkan API.
*  [3DMark](https://www.futuremark.com/pressreleases/compare-vulkan-and-directx-12-performance-with-3dmark) - 3DMark API Overhead test.

## Samples
*  Khronos [Vulkan samples](https://github.com/KhronosGroup/Vulkan-Samples) [[LICENSE](https://github.com/KhronosGroup/Vulkan-Samples/blob/master/LICENSE)]
*  Sascha Willems's [samples](https://github.com/SaschaWillems/Vulkan) and [Deferred rendering of Sponza](https://github.com/SaschaWillems/VulkanSponza) and his talk of [Khronos_meetup_munich](https://www.saschawillems.de/blog/2016/04/11/khronos-chapter-munich-vulkan-slides/).
*  (Incomplete) Sascha Willems's [samples port](https://github.com/jvm-graphics-labs/Vulkan) to Kotlin
*  Sascha Willems's [Vulkan-glTF-PBR](https://github.com/SaschaWillems/Vulkan-glTF-PBR) - physical based rendering with Vulkan using glTF 2.0 models. [MIT]
*  [Vulkan Best Practice for Mobile Developers Samples](https://github.com/ARM-software/vulkan_best_practice_for_mobile_developers)
*  Google
    *  [Android port of LunarG samples](https://github.com/googlesamples/vulkan-basic-samples).
    *  [android tutorials](https://github.com/googlesamples/android-vulkan-tutorials).
*  [nvpro-samples](https://github.com/nvpro-samples) - NVIDIA DesignWorks Samples. [[LICENSE](https://github.com/nvpro-samples/gl_vk_threaded_cadscene/blob/master/LICENSE)]
    *  [gl_vk_chopper](https://github.com/nvpro-samples/gl_vk_chopper) - Simple vulkan rendering example.
    *  [gl_vk_threaded_cadscene](https://github.com/nvpro-samples/gl_vk_threaded_cadscene) - OpenGL and Vulkan comparison on rendering a CAD scene using veraious techniques and [the blog](https://developer.nvidia.com/vulkan-opengl-threaded-cad-scene-sample) about it.
    *  [gl_vk_bk3dthreaded](https://github.com/nvpro-samples/gl_vk_bk3dthreaded) - Vulkan sample rendering 3D with 'worker-threads'.
    *  [gl_vk_supersampled](https://github.com/nvpro-samples/gl_vk_supersampled) - Vulkan sample showing a high quality super-sampled rendering.
*  [NVIDIA GameWorks Samples](https://github.com/NVIDIAGameWorks/GraphicsSamples) - GameWorks cross-platform graphics API samples. [[LICENSE](https://github.com/NVIDIAGameWorks/GraphicsSamples/blob/master/license.txt)]
*  [LunarG's Samples](https://github.com/LunarG/VulkanSamples)
*  [vkcube](https://github.com/krh/vkcube) - 'vkcube' sample from krh, works under X, wayland and VT console with
drm/kms.
*  [Stardust from Intel](https://github.com/GameTechDev/stardust_vulkan) - The Stardust sample application uses the Vulkan graphics API to efficiently render a cloud of animated particles. [[LICENSE](https://github.com/GameTechDev/stardust_vulkan/blob/master/license.txt)]
*  [Vulkan Quake port based on QuakeSpasm](https://github.com/Novum/vkQuake).
*  [C# Samples](https://github.com/FacticiusVir/SharpVk-Samples) - Port of Overv's tutorials to [SharpVk](https://github.com/FacticiusVir/SharpVk) [MIT]
*  [Vulkan-Forward-Plus-Renderer](https://github.com/WindyDarian/Vulkan-Forward-Plus-Renderer) - VFPR - a Vulkan Forward Plus Renderer. [MIT]
*  [Laugh Engine](https://github.com/jian-ru/laugh_engine) - Vulkan implementation of real-time PBR renderer.
*  [tinyrenderers](https://github.com/chaoticbob/tinyrenderers) - Single header implemenations of Vulkan and D3D12 renderers.
*  [TLVulkanRenderer](https://github.com/trungtle/TLVulkanRenderer) - Simple Vulkan-based renderer for my master thesis on real-time transparency. [CC BY-SA 4.0]
*  [Vulkan-Hpp Samples](https://github.com/jherico/Vulkan) - Fork of Sascha Willems excellent Vulkan examples that uses Vulkan-Hpp.
*  [SDF Font Demo](https://github.com/kocsis1david/font-demo) - Text rendering in Vulkan by estimating signed distance. [MIT]
*  [vulkantoy](https://github.com/jpystynen/vulkantoy) - Shadertoy image shader test app with Vulkan. [MIT]
*  [GL_vs_VK](https://github.com/RippeR37/GL_vs_VK) - Comparison of OpenGL and Vulkan API in terms of performance. [MIT]
*  [Vulkan Basic Graphics Samples](https://github.com/vcoda/basic-graphics-samples) - Collection of simple graphics samples that are written using Magma library.
*  [Simple RTX Vulkan raytracing tutorials](https://github.com/iOrange/rtxON). [MIT]
*  [RadX](https://github.com/world8th/RadX) - Dedicated example of radix sorting on GPU (on NVIDIA RTX in particular).
*  [Ray Tracing In One Weekend (Vulkan RTX)](https://github.com/GPSnoopy/RayTracingInVulkan) - Implementation of Peter Shirley's Ray Tracing In One Weekend book using Vulkan and NVIDIA's RTX extension.
*  [Gears VK](https://github.com/jeffboody/gearsvk) - Gears VK is a heavily modified port of the famous "gears" demo to Vulkan/Android/Linux. [MIT]
*  [Hello Triangle](https://github.com/helixd-2k18/VK_KHR_ray_tracing), based on `VK_KHR_ray_tracing` extension. [MIT]

## Libraries
*  [Acid](https://github.com/Equilibrium-Games/Acid) - A high speed C++17 Vulkan game engine. [MIT]
*  [bgfx](https://github.com/bkaradzic/bgfx#bgfx---cross-platform-rendering-library) - Cross-platform, graphics API agnostic, "Bring Your Own Engine/Framework" style rendering library. [[BSD-2-clause](https://github.com/bkaradzic/bgfx/blob/master/LICENSE)]
*  [bsf](https://github.com/GameFoundry/bsf) - Modern C++14 library for the development of real-time graphical applications. [MIT]
*  [Cinder](https://github.com/cinder/Cinder) and [the story](https://libcinder.org/notes/vulkan) [behind](https://forum.libcinder.org/#Topic/23286000002614007). [BSD]
*  [Diligent Engine](https://github.com/DiligentGraphics/DiligentEngine) - a modern cross-platform low-level graphics library that supports OpenGL/GLES, Direct3D11/12 and Vulkan. [Apache License 2.0]
*  [SDL](https://discourse.libsdl.org/t/sdl-2-0-6-released/23109) - added cross-platform Vulkan graphics support in SDL_vulkan.h. [zlib]
*  [DemoFramework](https://github.com/NXPmicro/gtec-demo-framework) - NXP GTEC C++11 cross-platform demo framework including lots of samples for Vulkan, OpenGL ES, OpenVX, OpenCL, OpenVG and OpenCV. [[BSD-3-clause](https://github.com/NXPmicro/gtec-demo-framework/blob/master/License.md)]
*  [openFrameworks](https://github.com/openframeworks-vk/openFrameworks) - the most famouse C++ creative coding framework. [MIT]
*  [PowerVR SDK](https://github.com/powervr-graphics/Native_SDK) - C++ cross-platform 3D graphics SDK to speed up development of Vulkan and GLES. [[LICENSE](https://github.com/powervr-graphics/Native_SDK/blob/4.1/LICENSE_POWERVR_SDK.txt)]
*  [glfw](https://github.com/glfw/glfw) and [the guide](http://www.glfw.org/docs/3.2/vulkan.html).  [[LICENSE](https://github.com/glfw/glfw/blob/master/LICENSE.md)]
*  [MoltenVK](https://github.com/KhronosGroup/MoltenVK/) - run Vulkan on iOS and macOS. [Apache-2.0]
*  [imgui](https://github.com/ocornut/imgui) - Immediate Mode Graphical User interface. [MIT]
*  [vuh](https://github.com/Glavnokoman/vuh) - Vulkan-based C++ GPGPU computing framework. [MIT]
*  [liblava](https://github.com/liblava/liblava) - A modern C++ and easy-to-use framework. [MIT]
*  [libvc](https://github.com/alexhultman/libvc) - Vulkan Compute for C++.  [[LICENSE](https://github.com/alexhultman/libvc/blob/master/LICENSE)]
*  [AMD's Anvil](https://github.com/GPUOpen-LibrariesAndSDKs/Anvil) - cross-platform framework for Vulkan. [[LICENSE](https://github.com/GPUOpen-LibrariesAndSDKs/Anvil/blob/master/LICENSE.txt)]
    * [Introductory Vulkan sample](https://github.com/GPUOpen-LibrariesAndSDKs/HelloVulkan). [MIT]
*  [Vulkan Memory Allocator](https://github.com/GPUOpen-LibrariesAndSDKs/VulkanMemoryAllocator) - Easy to integrate Vulkan memory allocation library from AMD. [MIT]
*  [V-EZ](https://github.com/GPUOpen-LibrariesAndSDKs/V-EZ) - light-weight middleware layer for the Vulkan API targeting Professional Workstation ISVs. [MIT]
*  [Google's vulkan-cpp-library](https://github.com/google/vulkan-cpp-library) - Vulkan abstraction library using C++11 for memory, resource management, type and thread safety as well as system independency. [Apache]
*  [Vookoo](https://github.com/andy-thomason/Vookoo) - Vookoo is a set of dependency-free utilities to assist in the construction and updating of Vulkan graphics data structres. [MIT]
*  [vpp](https://github.com/nyorain/vpp) - Modern C++ Vulkan Abstraction focused on performance and a straightforward interface. [MIT]
*  [Intrinsic Engine](https://github.com/begla/Intrinsic) - Intrinsic is a Vulkan based cross-platform graphics and game engine. [Apache License 2.0]
*  [glo / OpenGL Overload](https://github.com/g-truc/glo) - OpenGL implementation on top of Vulkan.
*  [Skia](https://skia.googlesource.com/skia) - Google's 2D graphics library has a [Vulkan](https://skia.org/user/special/vulkan) [backend](https://github.com/google/skia/tree/master/src/gpu/vk), demonstrated in a cross-platform [sample application](https://skia.org/user/sample/viewer) with its own [window library](https://github.com/google/skia/tree/master/tools/viewer). [BSD 3-clause] [website](https://skia.org)
*  [Spectrum](https://github.com/mwalczyk/spectrum_core) - Work-in-progress framework and abstraction layer around Vulkan.
*  [VkHLF](https://github.com/nvpro-pipeline/VkHLF) - Vulkan High Level Framework. [[LICENSE]](https://github.com/nvpro-pipeline/VkHLF/blob/master/LICENSE.txt)
*  [VulkanOnD3D12](https://github.com/Chabloom/VulkanOnD3D12) - Vulkan API for D3D12. [Apache License 2.0]
*  [visor](https://github.com/baldurk/visor) - Vulkan Ignoble Software Rasterizer. [MIT]
*  [Lugdunum](https://github.com/Lugdunum3D/Lugdunum) - Modern cross-platform 3D rendering engine built with Vulkan and modern C++14. [MIT]
*  [Vulkan-WSIWindow](https://github.com/renelindsay/Vulkan-WSIWindow) - Multi-platform library to create a Vulkan window, and handle input events. [Apache License 2.0]
*  [Falcor](https://github.com/NVIDIAGameWorks/Falcor) - Real-time rendering framework from NVIDIA, supporting DX12 and Vulkan. [BSD 3-clause]
*  [The-Forge](https://github.com/ConfettiFX/The-Forge) - DirectX 12, Vulkan, macOS Metal 2 rendering framework. [Apache License 2.0]
*  [FrameGraph](https://github.com/azhirnov/FrameGraph) - Vulkan abstraction layer that represent frame as a task graph. [BSD 2-clause]
*  [VK9](https://github.com/disks86/VK9) - Direct3D 9 compatibility layer using Vulkan
*  [gfx-rs](https://github.com/gfx-rs/gfx) - High-performance, bindless graphics API for Rust. [Apache License 2.0]
*  [vRt](https://github.com/world8th/vRt) - Vulkan API (>=1.1) based unified ray tracing library. [LGPL-3.0]
*  [rostkatze](https://github.com/msiglreith/rostkatze) - C++ implementation of Vulkan sitting on D3D12 🐈[Apache License 2.0]
*  [Fossilize](https://github.com/Themaister/Fossilize) - serialization format for various persistent Vulkan object types. [MIT]
*  [VulkanSceneGraph](https://github.com/vsg-dev) - Vulkan/C++17 scene graph project, successor to [OpenSceneGraph](http://www.openscenegraph.org).
*  [clspv](https://github.com/google/clspv) - prototype compiler for a subset of OpenCL C to Vulkan compute shaders. [Apache License 2.0]
*  [Pumex](https://github.com/pumexx/pumex) - cross-platform Vulkan renderer implementing frame graph and simple scene graph. Able to render on many surfaces at once [MIT]
*  [VUDA](https://github.com/jgbit/vuda) - header-only lib that provides a CUDA Runtime API interface. [MIT]
*  [Zink](https://gitlab.freedesktop.org/kusma/mesa/tree/zink) - OpenGL implementation on top of Vulkan, part of Mesa project. [MIT]
*  [ncnn](https://github.com/Tencent/ncnn) - High-performance neural network inference framework with Vulkan based GPU inference. [BSD 3-clause]
*  [iMSTK](https://gitlab.kitware.com/iMSTK/iMSTK) - C++ toolkit for building surgical simulations with Vulkan and VTK backends. [Apache License 2.0]
*  [Quartz](https://github.com/Nadrin/Quartz) - Physically based Vulkan RTX path tracer with a declarative ES7-like scene description language. [LGPL-3.0]	
*  [VK²](https://github.com/kotlin-graphics/vkk), Kotlin Wrapper for Vulkan: code expressiveness and safety meet graphic power [Apache License 2.0]
*  [small3d](https://www.gamedev.net/projects/515-small3d/), Tiny Vulkan based C++ cross-platform game development framework [BSD 3-clause]
*  [vkt/vkh](https://github.com/world8th/vkt), helper for Vulkan API (1.1), based and uses C++20. [MIT]

## Bindings
*  [ash](https://github.com/MaikKlein/ash) - Vulkan bindings for Rust. [MIT]
*  [libvulkan.lua](https://github.com/CapsAdmin/ffibuild/blob/master/vulkan/vulkan.lua) - Lua bindings for Vulkan.
*  [dvulkan](https://github.com/ColonelThirtyTwo/dvulkan) - Auto-generated D bindings for Vulkan.
*  [ErupteD](https://github.com/ParticlePeter/ErupteD) - Another Auto-generated D bindings for Vulkan.
*  [flextGL](https://github.com/mosra/flextgl) - Minimal Vulkan header/loader generator and [the blog post](http://blog.magnum.graphics/hacking/simple-efficient-vulkan-loading-with-flextgl/) about it.
*  [vulkan](https://github.com/expipiplus1/vulkan) - Haskell bindings for Vulkan and Vulkan Memory Allocator [BSD-3-Clause]
*  [nvk](https://github.com/maierfelix/nvk) - JavaScript bindings for Vulkan. [MIT]
*  [racket-vulkan](https://github.com/zyrolasting/racket-vulkan) - Racket bindings for Vulkan with [detailed implementation notes](https://sagegerard.com/racket-vulkan-notes-index.html). [MIT]
*  [Vulkan-hpp](https://github.com/KhronosGroup/Vulkan-Hpp) Open-Source Vulkan C++ API originated from NVIDIA and [the blog](https://developer.nvidia.com/open-source-vulkan-c-api) about it.
*  [VulkanSharp](https://github.com/mono/VulkanSharp) - C# bindings for Vulkan. [MIT]
*  [Vulkano](https://github.com/vulkano-rs/vulkano) - Safe and rich Rust wrapper around the Vulkan API. [MIT]
*  [LWJGL](https://www.lwjgl.org/) - Lightweight Java Game Library 3 has Vulkan bindings. [BSD]
*  [SharpVk](https://github.com/FacticiusVir/SharpVk) - C# bindings for Vulkan with Linq-to-SPIR-V & [NuGet package](https://www.nuget.org/packages/SharpVk). [MIT]
*  [vulkan](https://github.com/realitix/vulkan) - Ultimate Python bindings for Vulkan generated with CFFI. [Apache Licence 2.0]
*  [vulkan-go](https://github.com/vulkan-go/vulkan) - Go bindings for Vulkan. [MIT]
*  [PasVulkan](https://github.com/BeRo1985/pasvulkan) - Vulkan bindings plus high-level wrapper library for Object Pascal [Zlib]

## Tools
*  [Nsight™ Visual Studio Edition 5.2+](https://developer.nvidia.com/nvidia-nsight-visual-studio-edition).
*  [LoaderAndValidationLayers](https://github.com/KhronosGroup/Vulkan-LoaderAndValidationLayers) - from KhronosGroup. [Apache Licence 2.0]
*  [renderdoc](https://github.com/baldurk/renderdoc) - by baldurk, a stand-alone graphics debugging tool. [MIT]
    * [RDCtoVkCpp](https://github.com/azhirnov/RDCtoVkCpp) - converts RenderDoc Vulkan capture to compilable and executable C++ code. [MIT]
*  [VulkanTools](https://github.com/LunarG/VulkanTools) - LunarG's tools including layers, `vktrace` and `vkreplay`. [Apache Licence 2.0]
*  [CodeXL](https://github.com/GPUOpen-Tools/CodeXL) - CodeXL goes open source. [MIT]
*  [Qualcomm GPU Tools](https://developer.qualcomm.com/software/adreno-gpu-sdk/tools).
*  [Arm Mobile Studio](https://www.arm.com/products/development-tools/graphics/arm-mobile-studio) - includes the Arm Graphics Analyzer to trace graphics performance issues easily, and Arm Streamline performance analyzer, for a whole-system view of performance to determine bottlenecks quickly across both the CPU and GPU.
*  [Open Capture and Analytics Tool (OCAT)](https://github.com/GPUOpen-Tools/OCAT) - rovides an FPS overlay and performance measurement for D3D11, D3D12, and Vulkan. [MIT]
*  [gapid](https://github.com/google/gapid) - Graphics API Debugger, can trace and replay Android OpenGL ES and Vulkan applications. [Apache License 2.0]
*  [Arm - PerfDoc](https://github.com/ARM-software/perfdoc) - a validation layer against the Mali Application Developer Best Practices document. [MIT]
*  [glsl_trace](https://github.com/azhirnov/glsl_trace) - library for shader debugging and profiling for Vulkan and OpenGL. [MIT]


## Books
* [Introduction to Computer Graphics and the Vulkan API](https://www.amazon.com/Introduction-Computer-Graphics-Vulkan-API/dp/1548616176) by **Kenwright** - Introduce the reader to the exciting topic of computer graphics from a grounds-up practical perspective with the Vulkan API.
* [Learning Vulkan](https://www.amazon.com/Learning-Vulkan-Parminder-Singh/dp/1786469804) - by **Parminder Singh** - Get started with the Vulkan API and its programming techniques using the easy-to-follow examples.
  * [Book's Examples](https://github.com/PacktPublishing/Learning-Vulkan)
* [Vulkan Cookbook](https://www.amazon.com/Vulkan-Cookbook-Pawel-Lapinski/dp/1786468158)- by **Pawel Lapinski** - Explores a wide range of graphics programming and GPU compute methods to make the best use of the Vulkan API.
  * [Book's Examples](https://github.com/PacktPublishing/Vulkan-Cookbook)
* [Vulkan Programming Guide](https://www.amazon.com/Vulkan-Programming-Guide-Official-Learning/dp/0134464540) - by **Graham Sellers** and **John Kessenich** - Introduces powerful 3D development techniques for many fields.

## Khronos
*  Specification
    *  [Vulkan 1.0 Specification](https://www.khronos.org/registry/vulkan/specs/1.0/pdf/vkspec.pdf)
    *  [Vulkan 1.0 Specification with Extensions ](https://www.khronos.org/registry/vulkan/specs/1.0-extensions/pdf/vkspec.pdf)
    *  [Vulkan 1.0 Specification with WSI Extensions](https://www.khronos.org/registry/vulkan/specs/1.0-wsi_extensions/pdf/vkspec.pdf)
    *  [Vulkan 1.1 Specification](https://www.khronos.org/registry/vulkan/specs/1.1/pdf/)
    *  [Vulkan 1.1 Specification with Extensions ](https://www.khronos.org/registry/vulkan/specs/1.1-extensions/pdf/vkspec.pdf)
    *  [Vulkan 1.1 Specification with KHR Extensions](https://www.khronos.org/registry/vulkan/specs/1.1-khr-extensions/pdf/)
*  Quick Reference Sheets
    *  [Vulkan 1.0 Quick Reference Sheets](https://www.khronos.org/registry/vulkan/specs/1.0/refguide/Vulkan-1.0-web.pdf)
    *  [Vulkan 1.1 Quick Reference Sheets](https://www.khronos.org/registry/vulkan/specs/1.1/refguide/Vulkan-1.1-web.pdf)
*  [Conformance Tests (CTS)](https://github.com/KhronosGroup/Vulkan-CTS)
*  Conferences and Presentations
    *  [GDC 2016 Presentations](https://www.khronos.org/developers/library/2016-gdc)
    *  [2016 UK Chapter: Moving to Vulkan](https://www.khronos.org/developers/library/2016-uk-chapter-moving-to-vulkan)
    *  [SIGGRAPH 2016 BOF - Vulkan](https://www.youtube.com/watch?v=CsHMiEQgrLA)
    *  [SIGGRPAH 2016 Best Practices Roundtable](https://www.youtube.com/watch?v=owuJRPKIUAg)
    *  [2016 Vulkan DevDay UK](https://www.khronos.org/developers/library/2016-vulkan-devday-uk)
    *  [2016 Vulkan DevDay Seoul](https://www.khronos.org/developers/library/2016-Vulkan-DevU-Seoul)
    *  [2017 Vulkan DevU Vancouver](https://www.khronos.org/developers/library/2017-vulkan-devu-vancouver)
    *  [2017 Vulkan Loader Webinar](https://www.khronos.org/developers/library/2017-vulkan-loader-webinar)
    *  [SIGGRAPH 2017 BOF - Vulkan](https://www.youtube.com/watch?v=Nx0u-9ZwrmQ)
    *  [2018 Vulkan Montreal Dev Day](https://www.khronos.org/developers/library/2018-vulkan-montreal-dev-day)
    *  [2018 Vulkanised!](https://www.khronos.org/developers/library/2018-vulkanised)
    *  [SIGGRAPH 2018 BOF - Vulkan](https://www.youtube.com/watch?v=FCAM-3aAzXg&t=18350s)

## Community
*  [Freenode IRC](http://webchat.freenode.net/?channels=Vulkan)
*  [Google Plus](https://plus.google.com/communities/108983304183191634377)
*  [Khronos Forum](https://forums.khronos.org/forumdisplay.php/114-Vulkan)
*  [Reddit](https://www.reddit.com/r/vulkan/)
*  [Stack Overflow](http://stackoverflow.com/questions/tagged/vulkan)
*  [Discord](https://discord.gg/JyJDbyH)

## Related lists
*  [awesome](https://github.com/sindresorhus/awesome) - Curated list of awesome lists.
*  [awesome-opengl](https://github.com/eug/awesome-opengl) - Curated list of awesome OpenGL libraries, debuggers and resources.
*  [gamedev](https://github.com/ellisonleao/magictools) - Awesome list about game development.
*  [graphics-resources](https://github.com/mattdesl/graphics-resources) - List of graphic programming resources.
*  [awesome-d3d12](https://github.com/vinjn/awesome-d3d12) - Curated list of awesome D3D12 libraries, debuggers and resources.

## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## Contributing
Please see [CONTRIBUTING](https://github.com/vinjn/awesome-vulkan/blob/master/CONTRIBUTING.md) for details.
