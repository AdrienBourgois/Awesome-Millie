# Awesome-Millie :sparkles:

Welcome to **Awesome-Millie**!

This is a curated collection of useful links and resources, gathered over the course of various projects I've assigned to my students. You'll find a wide range of topics covered here, from advanced C++ concepts, game engine development, to shader programming, mathematics for game development, and everyday development tools.

I hope this collection will be as helpful to others as it has been for my students. Whether you're learning, teaching, or just exploring new topics, feel free to dive in and find something useful.

Enjoy, and happy coding! :rocket: #ILikeEmojis

## Table of Contents

- :computer: [Advanced C++ Concepts](#advanced-c-concepts)
- :video_game: [Game Engine Development](#game-engine-development)
- :framed_picture: [SFML Resources](#sfml-resources)
- :video_game: [Unreal Engine](#unreal-engine)
- :art: [Graphics Programming](#graphics-programming)
- :heavy_plus_sign: [Maths](#maths)
- :world_map: [Algorithms & Pathfinding](#algorithms--pathfinding)
- :bug: [Debugging & Profiling](#debugging--profiling)
- :hammer_and_wrench: [CMake & Build Systems](#cmake--build-systems)
- :seedling: [Git & Development Tools](#git--development-tools)
- :page_facing_up: [Technical Documentation](#technical-documentation)

## Advanced C++ Concepts

### General Reference :books:

- [cppreference](https://en.cppreference.com/index.html) : Community-maintained reference for the C++ language and standard library.

### Templates :scroll:

- [CppReference on Templates](https://en.cppreference.com/w/cpp/language/templates) : In-depth reference on templates, one of the most powerful features in C++.
  - *Templates* in C++ allow you to write generic functions and classes that can operate with any data type. They are particularly useful for creating reusable code components.
- [enable_if](https://en.cppreference.com/w/cpp/types/enable_if) : Documentation on `enable_if`, used for SFINAE (Substitution Failure Is Not An Error).
  - *SFINAE* is a C++ feature used in template programming that allows the compiler to choose the correct function template overload by checking if a certain condition is true.
- [Type traits](https://en.cppreference.com/w/cpp/header/type_traits) : A reference for type traits, essential tools in modern C++ template programming.
- [SFINAE](https://en.cppreference.com/w/cpp/language/sfinae) : Detailed explanation of SFINAE in C++, used in advanced template programming.
- [Variadic Templates (French)](https://laefy.github.io/CPP_Learning/chapter10/2-variadiac/) : A worked introduction to parameter packs, pack expansion, perfect forwarding, and fold expressions.

### Type Casting :repeat:

- [static_cast<>](https://en.cppreference.com/w/cpp/language/static_cast) : Documentation on `static_cast`, used for explicit type conversions in C++.
- [User-Defined Conversion Functions](https://en.cppreference.com/w/cpp/language/cast_operator.html) : Define conversions from class types, including explicit conversion operators and their interaction with overload resolution.

### Vectors and Containers :package:

- [Visual list of containers](https://hackingcpp.com/cpp/std/containers.html) : A visual guide to all standard containers in C++.
- [std::vector tutorial](https://hackingcpp.com/cpp/std/vector.html) : A detailed tutorial on how to use `std::vector`, the most common container in C++.
- [std::vector cheat sheet](https://hackingcpp.com/cpp/std/vector_crop.png) : A concise cheat sheet for using `std::vector`.
- [CppReference on std::vector](https://en.cppreference.com/w/cpp/container/vector) : Reference documentation for `std::vector`.

### Operator Overloading :heavy_plus_sign:

- [CppReference on Operators](https://en.cppreference.com/w/cpp/language/operators) : Reference on operator overloading in C++.
- [Arithmetic Operators](https://en.cppreference.com/w/cpp/language/operator_arithmetic) : Explanation of how to overload arithmetic operators in C++.

### Pointers :pushpin:

- [Pointer tutorial](https://hackingcpp.com/cpp/lang/pointers.html) : A visual guide to understanding pointers, an essential concept in C++ programming.
- [Smart Pointers (Microsoft Learn)](https://learn.microsoft.com/en-us/cpp/cpp/smart-pointers-modern-cpp?view=msvc-170) : An introduction to `std::unique_ptr`, `std::shared_ptr`, and `std::weak_ptr` for expressing ownership and managing object lifetimes.

### Object-Oriented Programming :classical_building:

- [Virtual Functions](https://en.cppreference.com/w/cpp/language/virtual) : Learn about virtual functions in C++ and how they are used for polymorphism.
  - *Virtual functions* allow you to override functions in derived classes and are a cornerstone of runtime polymorphism in C++.
- [Abstract Classes](https://en.cppreference.com/w/cpp/language/abstract_class) : Explanation of abstract classes, which cannot be instantiated and are meant to be used as base classes.
- [Rule of 3/5/0](https://en.cppreference.com/w/cpp/language/rule_of_three) : A guide to understanding constructors and destructors in C++.

### Unit Testing :test_tube:

- [Creating Unit Test Projects](https://learn.microsoft.com/en-us/visualstudio/test/writing-unit-tests-for-c-cpp?view=vs-2022) : A guide to setting up unit test projects in Visual Studio.
- [C++ Unit Test Framework API](https://learn.microsoft.com/en-us/visualstudio/test/microsoft-visualstudio-testtools-cppunittestframework-api-reference?view=vs-2022) : API reference for Microsoft's native C++ unit testing framework in Visual Studio.

### Iterators :trackball:

- [Iterator Library](https://en.cppreference.com/w/cpp/iterator) : Reference documentation on iterators, which allow you to traverse containers in C++.

### Forward Declarations :arrow_forward:

- [Forward Declarations Explanation](https://stackoverflow.com/questions/4757565/what-are-forward-declarations-in-c/4757718#4757718) : A Stack Overflow post explaining what forward declarations are and why they are useful in C++.
- [CppReference on Forward Declarations](https://en.cppreference.com/w/cpp/language/class) : Reference documentation for class declarations in C++.
  - A *forward declaration* allows you to declare the existence of a class or function before you define it. This is useful in reducing compile-time dependencies in C++.

### Preprocessor & Windows Headers :gear:

- [Predefined Macros (MSVC)](https://learn.microsoft.com/en-us/cpp/preprocessor/predefined-macros?view=msvc-170) : Standard macros such as `__FILE__` and `__LINE__`, alongside Microsoft-specific macros for compiler and platform detection.
- [Using the Windows Headers](https://learn.microsoft.com/en-us/windows/win32/winprog/using-the-windows-headers) : Windows SDK header configuration, including `WIN32_LEAN_AND_MEAN` to reduce the headers included by `Windows.h`.

---

## Game Engine Development

### Architecture & Patterns :building_construction:

- [Game Programming Patterns](https://gameprogrammingpatterns.com/contents.html) : Robert Nystrom's freely available book on patterns used in games, including State, Observer, Component, and Object Pool. Read the trade-offs before adopting a pattern.
- [SFML Discovery Engine](https://github.com/AdrienBourgois/SFML-Discovery-Engine) : My educational micro engine with Unity-inspired scenes, game objects, components, and an ImGui debug interface. Includes a Visual Studio solution and bundled dependencies; useful for studying a small engine's structure.
- [Component Pattern](https://gameprogrammingpatterns.com/component.html) : Separate an entity's responsibilities into components while examining the resulting complexity and communication trade-offs.
- [Building Your Own Engine: A GDC Perspective](https://www.gamedeveloper.com/programming/why-and-how-you-should-leave-unity-and-unreal-to-make-your-own-engine) : Coverage of Rez Graham's GDC 2024 talk on custom game technology. A viewpoint to evaluate against your project's needs and costs.

### Game Loop & Timing :stopwatch:

- [Unity Event Function Execution Order](https://docs.unity3d.com/Manual/execution-order.html) : Unity lifecycle and execution-order diagram, including initialization, physics, updates, and rendering. A concrete engine example, with Unity-specific behavior.
- [Fix Your Timestep!](https://gafferongames.com/post/fix_your_timestep/) : Glenn Fiedler explains variable and fixed timesteps, simulation stability, and interpolation between physics updates.
- [Game Loop](https://gameprogrammingpatterns.com/game-loop.html) : Coordinate input, simulation, and rendering while separating game time from processor speed.
- [Update Method](https://gameprogrammingpatterns.com/update-method.html) : Structure per-frame behavior across multiple game objects.

### Collision Detection :collision:

- [3D Collision Detection (MDN)](https://developer.mozilla.org/en-US/docs/Games/Techniques/3D_collision_detection) : Introduction to bounding volumes, including AABBs and spheres, with JavaScript examples and transferable geometry.
- [AABB 2D Collision Detection](https://kishimotostudios.com/articles/aabb_collision/) : A compact explanation of axis-aligned rectangle overlap, with diagrams and a JavaScript implementation.
- [Collision Detection (LearnOpenGL)](https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-detection) : AABB and circle-to-AABB collision tests in a Breakout-style game, with C++ examples. The collision mathematics also applies outside OpenGL.

### API Graphics Tutorials :desktop_computer:

- [Vulkan tutorial](https://docs.vulkan.org/tutorial/latest/00_Introduction.html) : A beginner-friendly guide to Vulkan, one of the most popular modern graphics APIs.
- [DX12 tutorial](https://www.braynzarsoft.net/viewtutorial/q16390-04-directx-12-braynzar-soft-tutorials) : Learn DirectX 12 through comprehensive tutorials.
- [DX11 tutorial](https://www.braynzarsoft.net/viewtutorial/q16390-braynzar-soft-directx-11-tutorials) : A set of tutorials for working with DirectX 11.
- [OpenGL tutorial](https://www.opengl-tutorial.org/) : A structured guide to learning OpenGL for real-time rendering.
- [Alternative OpenGL tutorial](https://paroj.github.io/gltut/) : Another useful source to learn OpenGL from scratch.
- [DirectX 11 Tutorials (Rastertek)](https://www.rastertek.com/tutdx11win10.html) : A progressive series covering a rendering framework, shaders, lighting, shadows, and other Direct3D 11 techniques on Windows.

### Cross-API Resources :globe_with_meridians:

- [Decoder Ring (API object translation)](https://docs.vulkan.org/guide/latest/decoder_ring.html) : A comparison of how objects and functions translate between Vulkan and other graphics APIs.
- [Dear ImGui](https://github.com/ocornut/imgui) : A C++ library for building tools, inspectors, and debug interfaces, with backends for multiple platforms and rendering APIs.
- [Dear ImGui Interactive Manual](https://pthom.github.io/imgui_manual_online/manual/imgui_manual.html) : A community-maintained browser demo for exploring ImGui widgets and their associated code.
- [GLFW](https://www.glfw.org/) : Create desktop windows, handle input, and manage OpenGL contexts or support Vulkan surface creation.

### Vulkan-Specific Resources :volcano:

- [Vulkan in 30 minutes](https://renderdoc.org/vulkan-in-30-minutes.html) : A crash course on Vulkan, aimed at providing a high-level understanding of the API.
- [Vulkan Reference Guide](https://www.khronos.org/files/vulkan11-reference-guide.pdf) : A detailed reference manual for Vulkan 1.1, can be downloaded from the [Khronos Reference Guides](https://www.khronos.org/developers/reference-cards/).
- [Vulkan Documentation](https://docs.vulkan.org/spec/latest/index.html) : The official documentation of the Vulkan API.
- [SIGGRAPH Presentation](https://web.engr.oregonstate.edu/~mjb/vulkan/Handouts/ABRIDGED.1pp.pdf) : A presentation on Vulkan from the SIGGRAPH conference, which offers insights into its practical use.
- [Vulkan-Hpp](https://github.com/KhronosGroup/Vulkan-Hpp) : Khronos C++ bindings for Vulkan, with stronger type checking, convenience wrappers, and RAII handle options.

### DirectX-Specific Resources :x:

- [Microsoft DirectX 12 Documentation](https://learn.microsoft.com/en-us/windows/win32/direct3d12/directx-12-programming-guide) : The official guide to getting started with DirectX 12.
- [DirectX Toolkit](https://github.com/microsoft/DirectXTK12) : A toolkit for DirectX 12 that simplifies common tasks like loading textures and drawing primitives.
- [Living without D3DX](https://walbourn.github.io/living-without-d3dx/) : Chuck Walbourn's migration reference for replacing deprecated D3DX functionality when working through older DirectX code and tutorials.
- [Anatomy of Direct3D 12 Create Device](https://walbourn.github.io/anatomy-of-direct3d-12-create-device/) : Device initialization, adapter selection, feature levels, and debug-layer setup in Direct3D 12.

### OpenGL-Specific Resources :telescope:

- [GLFW Migration 2.X to 3.X](https://www.glfw.org/docs/3.0/moving.html) : A guide for developers who need to migrate from older versions of GLFW to version 3.x.
- [GLEW](https://glew.sourceforge.net/) : Load OpenGL core and extension entry points and query extension support after creating a context.

### Physics Libraries :collision:

- [PhysX](https://github.com/NVIDIA-Omniverse/PhysX) : NVIDIA's physics SDK for simulation and collision handling.
- [Bullet Physics](https://github.com/bulletphysics/bullet3) : A physics SDK for collision detection and dynamics, with examples for learning and integration.
- [Jolt Physics](https://github.com/jrouwe/JoltPhysics) : A C++ rigid-body physics and collision library designed to make use of multiple CPU cores.

### Audio Libraries & Middleware :musical_note:

- [miniaudio](https://miniaud.io/) : A compact C library for audio playback, capture, decoding, and mixing.
- [OpenAL Soft](https://openal-soft.org/) : A software implementation of the OpenAL API for spatial audio.
- [FMOD](https://www.fmod.com/) : Audio middleware with authoring tools and runtime integration for games.
- [Wwise](https://www.audiokinetic.com/) : Audiokinetic's audio authoring and runtime middleware for interactive sound.

---

## SFML Resources

The tutorials below target SFML 3.1, with API references pinned to 3.1.0. Select the matching documentation version for your project. Example repositories may bundle a different SFML version.

### SFML Basics :seedling:

- [SFML Website](https://www.sfml-dev.org/) : Official SFML website, downloads, and community links.
- [SFML 3.1 Tutorials](https://www.sfml-dev.org/tutorials/3.1/) : Official tutorials covering windows, events, graphics, audio, networking, and system utilities.
- [SFML 3.1 + Visual Studio](https://www.sfml-dev.org/tutorials/3.1/getting-started/visual-studio/) : Configure include paths, linker dependencies, and Debug/Release builds, with guidance for static and dynamic linking.
- [SFML 3.1.0 Documentation](https://www.sfml-dev.org/documentation/3.1.0/) : Official API reference.
- [Migrating from SFML 2 to SFML 3.0](https://www.sfml-dev.org/tutorials/3.1/migration/sfml-2/) : Essential API changes when adapting older tutorials or projects to SFML 3.
- [Migrating from SFML 3.0 to SFML 3.1](https://www.sfml-dev.org/tutorials/3.1/migration/sfml-3.0/) : Essential API changes when adapting older tutorials or projects to SFML 3.1.

### Time & Transforms :stopwatch:

- [Handling Time](https://www.sfml-dev.org/tutorials/3.1/system/time/) : Measure elapsed time with `sf::Clock`, use `sf::Time`, and update movement using delta time.
- [Position, Rotation, Scale & Origin](https://www.sfml-dev.org/tutorials/3.1/graphics/transform/) : Understand local and global transforms, sprite pivots, and combined transformations.

### Bounds & Intersections :wrench:

- [sf::Rect::findIntersection()](https://www.sfml-dev.org/documentation/3.1.0/classsf_1_1Rect.html) : Rectangle overlap in SFML 3: `findIntersection` returns an optional intersection rectangle. Use `contains` for point tests such as mouse hit detection.
- [sf::Sprite::getGlobalBounds()](https://www.sfml-dev.org/documentation/3.1.0/classsf_1_1Sprite.html) : Retrieve a sprite's axis-aligned bounds after transformation. This is a bounding-box test, not pixel-perfect collision detection.

### Shaders :sparkles:

- [Adding Special Effects with Shaders](https://www.sfml-dev.org/tutorials/3.1/graphics/shader/) : Official introduction to loading shaders, setting uniforms, and using them when drawing with SFML 3.
- [sf::Shader Reference](https://www.sfml-dev.org/documentation/3.1.0/classsf_1_1Shader.html) : API details for shader loading, uniforms, and availability checks.

---

## Unreal Engine

### Getting Started :seedling:

- [Unreal Engine Documentation](https://dev.epicgames.com/documentation/en-us/unreal-engine) : Epic's main documentation hub. Use the version selector to match your installed engine.
- [Unreal Garden](https://unreal-garden.com/tutorials/) : Practical community tutorials on Unreal C++, Blueprints, editor tooling, UMG, and related workflows.

### Blueprints & Gameplay :video_game:

- [Introduction to Blueprints](https://dev.epicgames.com/documentation/en-us/unreal-engine/introduction-to-blueprints-visual-scripting-in-unreal-engine) : An introduction to Unreal's visual scripting system and how it fits into gameplay development.
- [Blueprint Workflows](https://dev.epicgames.com/documentation/en-us/unreal-engine/blueprint-workflows-in-unreal-engine) : Epic's overview of workflows for creating and using Blueprints.
- [Gameplay Framework](https://dev.epicgames.com/documentation/en-us/unreal-engine/gameplay-framework-in-unreal-engine) : The roles and relationships of Actors, Pawns, Controllers, GameMode, and other gameplay classes.

### Materials :art:

- [Unreal Engine Materials](https://dev.epicgames.com/documentation/en-us/unreal-engine/unreal-engine-materials) : Material creation, properties, and the rendering concepts behind Unreal's surface appearance.
- [Materials Tutorials](https://dev.epicgames.com/documentation/en-us/unreal-engine/unreal-engine-materials-tutorials) : Epic's guided material examples, from introductory workflows to more advanced effects.

### Unreal Engine Shader Development :gear:

- [UE5 Shaders / Graphics Pipeline](https://dev.epicgames.com/documentation/unreal-engine/shader-development-in-unreal-engine) : The official guide to working with shaders and the graphics pipeline in Unreal Engine 5.

---

## Graphics Programming

### Parallax :mountain:

- [Parallax (Sketchplanations)](https://sketchplanations.com/parallax) : An illustrated explanation of apparent motion at different distances, useful for understanding layered scrolling backgrounds.

### Unity Shader Development :sparkles:

- [Unity Shaders Documentation](https://docs.unity3d.com/Manual/Shaders.html) : A complete guide to understanding and writing shaders in Unity.
- [Writing Shaders in Unity](https://docs.unity3d.com/Manual/shader-writing.html) : A tutorial on creating custom shaders using Unity's ShaderLab.
- [ShaderLab Reference](https://docs.unity3d.com/Manual/SL-Reference.html) : The reference documentation for Unity's ShaderLab language.
- [HLSL / CG Documentation](https://docs.unity3d.com/Manual/SL-ShaderPrograms.html) : Learn about High-Level Shader Language (HLSL) and Cg in Unity.
- [GLSL Documentation](https://docs.unity3d.com/Manual/SL-GLSLShaderPrograms.html) : Guide on using GLSL shaders in Unity.

### Shader Tools & Languages :toolbox:

- [ShaderGraph Documentation](https://docs.unity3d.com/Packages/com.unity.shadergraph@16.0/manual/index.html) : Learn to create shaders visually using Unity’s ShaderGraph.
- [Nvidia CG Documentation](https://developer.download.nvidia.com/cg/index_stdlib.html) : Comprehensive documentation for CG, Nvidia’s shading language.
- [HLSL Documentation](https://learn.microsoft.com/en-us/windows/win32/direct3dhlsl/dx-graphics-hlsl-writing-shaders-9) : Learn to write HLSL shaders, used across DirectX.
- [Shaders for Game Devs (Freya Holmér)](https://www.youtube.com/playlist?list=PLImQaTpSAdsCnJon-Eir92SZMl7tPBS4Z) : A video course on shaders and the mathematics used to build visual effects.

### Visual Explanations & Further Reading :video_camera:

- [How Do Video Game Graphics Work? (Branch Education)](https://www.youtube.com/watch?v=C8YtdC8mxTU) : A visual introduction to how game data becomes an image through the rendering pipeline.
- [PAUSE PROCESS (French)](https://www.youtube.com/@pauseprocess5711) : Accessible videos explaining techniques and technology used in games.
- [Computer Graphics Resources (legends2k)](https://legends2k.github.io/note/cg_resources/) : An annotated collection of graphics books, articles, courses, and other references for further exploration.

---

## Maths

### Coordinate Systems & Rotations :compass:

- [An Introduction to Quaternions (Gabor Makes Games)](https://gabormakesgames.com/quaternions.html) : A practical series on quaternion construction, multiplication, interpolation, and conversion to matrices.
- [3D Math Primer: Coordinate Systems](https://www.3dgep.com/3d-math-primer-for-game-programmers/) : Illustrated explanations of coordinate spaces, handedness, and transformations. The article uses traditional DirectX/OpenGL conventions; choose and document the conventions used by your own engine.

### Math Libraries :package:

- [GLM](https://github.com/g-truc/glm) : A C++ mathematics library with GLSL-style types and operations for vectors, matrices, transforms, and quaternions. Useful across graphics APIs.
- [DirectXMath](https://github.com/microsoft/DirectXMath) : Microsoft's inline SIMD C++ mathematics library for games and graphics. See the [API documentation](https://learn.microsoft.com/en-us/windows/win32/dxmath/directxmath-portal) for vectors, matrices, quaternions, and related operations.

### Visual Tools :triangular_ruler:

- [Matrix Multiplication Visual Tool](http://matrixmultiplication.xyz/) : A great tool to visually understand how matrix multiplication works.

### Useful Snippets :wrench:

- [Math Snippets](https://github.com/terkelg/math) : A collection of useful math snippets for programming, covering various topics from basic operations to more complex formulas.

### Freya Holmér's Visual Math :video_camera:

- [Freya Holmér's YouTube Channel](https://www.youtube.com/user/Acegikm0/videos) : A series of videos that explain mathematical concepts visually, with game programming examples, often with Unity examples.

### Gimbal Lock :lock:

- [Gimbal Lock Explanation](https://en.wikipedia.org/wiki/Gimbal_lock) : A detailed explanation of Gimbal Lock, a problem that arises in 3D rotations.

---

## Algorithms & Pathfinding

### Algorithms & Complexity :mag:

- [Introduction to A* (Red Blob Games)](https://www.redblobgames.com/pathfinding/a-star/introduction.html) : Interactive explanations of breadth-first search, Dijkstra, and A*, including frontiers, costs, and heuristics.
- [Big O with Code Examples (French)](https://loud-technology.com/blog/notation-grand-o-performance-complexite-algorithmique/) : An introductory comparison of common complexity classes using Python examples. Use it for growth-rate intuition; asymptotic complexity does not replace benchmarking.

### Real-World Map Data :world_map:

- [OpenStreetMap](https://www.openstreetmap.org/) : Explore a collaborative map and its geographic data as a starting point for graph and routing experiments.
- [Geofabrik Data Extracts](https://download.geofabrik.de/) : Download regional OpenStreetMap extracts. The [Île-de-France dataset](https://download.geofabrik.de/europe/france/ile-de-france.html) is one example for road-network projects.
- [OpenStreetMap Highway Tags](https://wiki.openstreetmap.org/wiki/Key:highway) : Understand how roads and paths are classified before selecting data for a graph. Routing also needs appropriate access and direction information.
- [Nominatim](https://nominatim.org/) : Geocoding and reverse geocoding with OpenStreetMap data: find places by name or retrieve an address from coordinates.

---

## Debugging & Profiling

### Graphics Debugging :bug:

- [RenderDoc](https://renderdoc.org/) : Capture frames and inspect rendering commands, resources, and pipeline state. See the [project repository](https://github.com/baldurk/renderdoc) for supported APIs and platforms.
- [NVIDIA Nsight Graphics](https://developer.nvidia.com/nsight-graphics) : NVIDIA's tools for graphics debugging and GPU performance analysis. Check hardware and API support for your setup.
- [OpenGL Debug Output](https://wikis.khronos.org/opengl/Debug_Output) : Receive diagnostic messages from OpenGL through debug callbacks and organize them by source, type, and severity.

### Native C++ Debugging :mag:

- [Natvis: Custom C++ Debugger Views](https://learn.microsoft.com/en-us/visualstudio/debugger/create-custom-views-of-native-objects?view=vs-2022) : Define how your engine's classes and containers appear in Visual Studio's debugger.

---

## CMake & Build Systems

### Build Performance :stopwatch:

- [Precompiled Headers & Unity Builds in CMake](https://onqtam.github.io/programming/2019-12-20-pch-unity-cmake-3-16/) : A practical article about the CMake 3.16 features for reducing compilation work, with their trade-offs. Here, unity builds mean combining source files for compilation.
- [CMake UNITY_BUILD Reference](https://cmake.org/cmake/help/latest/prop_tgt/UNITY_BUILD.html) : Current documentation on grouping sources, exclusions, and potential One Definition Rule problems.

### Custom Build Steps :wrench:

- [add_custom_command](https://cmake.org/cmake/help/latest/command/add_custom_command.html) : Define generated outputs or build events with commands and dependencies.
- [CMake Command-Line Tool](https://cmake.org/cmake/help/latest/manual/cmake.1.html) : Configure and build projects, and use `cmake -E` utilities for portable file and directory operations. Check individual command version requirements.

---

## Git & Development Tools

### Version Control :seedling:

- [Git Cheat Sheet](https://git-scm.com/cheat-sheet) : A command reference organized by task, including staging, branching, merging, and inspecting history.
- [GitHub Git Cheat Sheet (PDF)](https://education.github.com/git-cheat-sheet-education.pdf) : A printable two-page reference for everyday Git commands; useful beyond the classroom.
- [gitignore.io](https://www.toptal.com/developers/gitignore) : Generate a starting `.gitignore` for your operating system, IDE, and languages. Review the generated rules against your project's layout.
- [Git Tags (Pro Git)](https://git-scm.com/book/en/v2/Git-Basics-Tagging) : Create, inspect, and publish lightweight or annotated tags for identifiable project versions.
- [Learn Git Branching](https://learngitbranching.js.org/) : Interactive exercises for learning commits, branches, merges, rebases, and remote operations.
- [Visualizing Git](https://git-school.github.io/visualizing-git/) : A browser sandbox for seeing how Git commands change a commit graph.

### Commit Conventions & Releases :label:

- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) : An optional convention for structured commit messages, including change types and breaking changes.
- [Semantic Versioning](https://semver.org/) : A versioning convention that communicates compatibility changes to a declared public API through major, minor, and patch versions.
- [GitHub Autolinked References](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/autolinked-references-and-urls) : Reference issues, pull requests, and commits so GitHub turns them into navigable links.

### Organization & Reading :books:

- [Trello](https://trello.com/home) : Visual task boards for organizing individual projects or team work.
- [Feedly News Reader](https://feedly.com/news-reader) : Follow technical blogs and other RSS sources in one place, and organize reading by topic.

### Student Offers :mortar_board:

- [GitHub Student Developer Pack](https://education.github.com/pack) : Developer tools and service offers for eligible, verified students. Availability and individual offer conditions vary.

---

## Technical Documentation

### Technical Design Documents :page_facing_up:

These resources describe technical design documents. Adapt their sections to the actual project; a design document does not prescribe a test-driven development workflow.

- [Technical Design (Stanford University IT)](https://uit.stanford.edu/pmo/technical-design) : An overview of what a technical design document covers, with a linked template and Stanford's own review process.
- [The Technical Design Document (Game Development)](https://dlorenzolaguno17.github.io/TDD/) : A student-authored guide to documenting a game's technical goals, risks, architecture, tools, and relationship to the game design document. Treat the examples as suggestions.

### Writing & API Documentation :books:

- [GitHub Markdown Guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) : Format README files and project documentation with headings, lists, links, and code blocks.
- [Doxygen](https://www.doxygen.nl/index.html) : Generate browsable API documentation from source code and structured comments, including C++ projects.
