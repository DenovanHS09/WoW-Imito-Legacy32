
# WoW-Imito Legacy32
## ARM32 Porting Plan

### 1. Project Objective

Develop an experimental ARM32-compatible adaptation
of WoW-Imito for low-resource Android devices.

Initial reference device:
- Xiaomi Redmi A2 Plus
- MediaTek Helio G36
- 3 GB RAM
- Android 13

Target ABI:
- armeabi-v7a

### 2. Initial Game Target

World of Warcraft:
- Wrath of the Lich King 3.3.5a

The project will use the user's existing game
client for testing.

### 3. Compatibility Architecture

Components to investigate:

- Android application layer
- ARM32 native libraries
- Box86
- Wine x86 (32-bit)
- Linux ARMhf environment
- Graphics translation
- OpenGL / Vulkan compatibility
- Touch input system

### 4. Development Strategy

Phase 1: Repository audit.
Phase 2: Android architecture diagnostics.
Phase 3: ARM32 environment preparation.
Phase 4: Box86 and Wine compatibility.
Phase 5: Windows x86 application testing.
Phase 6: WotLK 3.3.5a execution.
Phase 7: Performance optimization.

### 5. Development Environment

Primary development:
- GitHub
- GitHub Web Editor
- GitHub Actions

Local testing:
- Termux
- Redmi A2 Plus

### 6. Technical Constraints

- 3 GB RAM
- PowerVR GE8320 GPU
- ARM32 application compatibility
- Limited local development resources

### 7. Project Principles

- Preserve upstream project history.
- Maintain an independent development branch.
- Avoid unnecessary modifications to upstream files.
- Respect third-party licenses.
- Do not redistribute proprietary game files.
- Document every compatibility experiment.

### 8. Initial Success Criteria

1. Identify all required native dependencies.
2. Establish an ARM32 execution environment.
3. Execute a basic Windows x86 application.
4. Test WoW WotLK 3.3.5a.
5. Measure memory consumption and performance.

Status: Experimental research.
