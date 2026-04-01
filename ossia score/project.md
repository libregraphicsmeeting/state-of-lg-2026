# ossia score

## Slide 1 speaker notes

ossia score is a cross-platform sequencer for audio-visual artists, 
designed to enable the creation of interactive shows, museum installations, 
intermedia digital artworks, interactive music and more in an intuitive user interface. 

## Slide 2 speaker notes

It allows to sequence OSC, MIDI, DMX, sound files and more, between multiple software and hardware.

TEXT:
✿ A show control system: supports every standard protocol used by media artists: OSC, DMX, MIDI, OSCQuery, MQTT, CoAP, HTTP, Websockets, and dozens of others.

✿ An audio and video real-time visual data flow graph (like PureData, Max/MSP, Touchdesigner, Usine, etc.)... Combined with a time-line supporting interactive cues!

✿ Works on Windows, macOS, Linux including embedded (RPi...). 

✿ Acts as a bridge between many environments / platforms / protocols and has a huge amount of integrations: FFMPEG, GStreamer, VST, LV2, VST3, CLAP, JSFX, ISF Shaders, Qt Quick, ONNX, LTC, etc.

✿ Also support a vast amount of audio / video formats for live media, with hw decoding and scrubbing (Vulkan Video! ProRes! HAP! DXV!), as well as a full GPU-only graphics pipeline (everything is based on raster and compute shaders. More general than e.g. TD POPs.)

✿ Used in award-winning art installations & performances (Ars Electronica, etc.)

## SLide 3 speaker notes
A talk and a workshop will be given during LGM 2026. 
The talk will give an overview of the graphics pipeline and feature of the software, 
and the workshop will be a hands-on exploration.

Jean-Michaël Celerier the main dev will be around during the entire event, feel free to bother him!

TEXT:
Milestones:
✿ StreamDiffusion: First Linux software to do this.

✿ Full-Dome immersive rendering pipeline.

✿ HDR support: creation of an HDR viewport when supported. Tonemapping pipeline, etc.

✿ Full Qt Quick integration for custom processes & pipelines. Case in point: this presentation system.

✿ Video mapping! 
With multi-projector support, soft-edge blending. The whole shtick. First OSS to support these features.

✿ Streaming, export and recording!
Deep FFMPEG and GStreamer integration allows stuff like WebRTC, rendering to AV1, etc.

Roadmap:
(help appreciated :D)
✿ Proper scene graph, not just passing geometry  & buffers around.

✿ Creating presets, demos, examples.

✿ Finish pipewire video input for zero-copy passing of DMA-BUF things around.

✿ Wayland advocacy for media arts use-cases.
→ Video mapping quite harder if you cannot control monitors programmatically

✿ Modern render pipelines: 
→ Raytracing (successful Vulkan prototype during GSoC 2025).
→ Mesh shader pipeline.
