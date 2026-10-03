# NovaFlare additive compatibility interfaces

Restores original static shared geometry and animation updateFrames. The optional shareGeometry constructor argument and paused flag remain compatibility stubs; they do not change original geometry sharing or frame updates.

The earlier broad integration changed existing behavior and is superseded by this repair. Compatibility additions must preserve existing NF calls, defaults and update/render/audio paths. Unsupported additions may return a neutral result instead of replacing a legacy implementation.

Windows x64 and Android ARMv7/ARM64/x86_64 native Lime binaries have been rebuilt. The full game targets Windows x64 and Android ARM64. Visual gameplay acceptance is performed manually by the project owner.
