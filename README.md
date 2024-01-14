# RazerTartarusV2Mods

> This project is still very much a WIP and is currently untested. I will keep this warning up until I feel it is ready, so if you're reading this I recommend holding off on building this project!

Don't like the Mecha-Membrane switches in your Razer Tartarus v2? How about switching out the D-Pad for an analog stick, or replacing the fixed cable with a detatchable USB-C connector? I've been using Razer's Tartarus line of gamepads since 2015 and have never looked back, but they're certainly not perfect. In this repo I aim to fix that by modifying parts of the Tartarus v2. These mods are designed to be reversable (mostly) and are made specifically with the Tartarus v2 in mind and may not all work on the Tartarus Pro. This is NOT a budget alternitive to a Tartarus Pro either. If you don't already have a Tartarus it will likely be more cost effective to just buy the Tartarus Pro depending on which mods you preform. I am doing this because I enjoy doing electronics projects, and I happened to have an extra Tartarus v2 laying around. If there are any mods you want that you don't see on this repo please use the "Feature Request" tag in the [Issues](https://github.com/g2bb/RazerTartarusV2Mods/issues) tab and let me know what it is. I'd love to out-engineer Razer here 👀.

So, enough preamble, on with the project. First let's define what mods we are attempting to do:
- [ ] Magnetic Palm Rest
- [ ] Detatchable USB-C (Non-completely reversable)
- [ ] Analog Stick
- [ ] D-Pad Relocate
- [ ] Full Mechanical Keyswitches
- [ ] Top Thumb Button Mechanical Keyswitch
- [ ] Wireless

## Magnetic Palm Rest
> This mod is still in the works to figure out how to make it simply and reversably. More to come!

I don't like the way the Tartarus V2 palm rest is reliant on a friction fit, it very quickly wears out and makes picking up and moving the device difficult.

## Detatchable USB-C cable
> I am currently waiting on my parts to arrive to start developing this mod. More to come!

I'm not a fan of fixed length cables. This is a super simple mod replacing the fixed cable with a standard USB-C connector. This can be done reversably by buying the CONNECTOR_NAME connector and proper USB-C Female breakout board online. Or if you're not concerned about puting it back together, the connector and wires can be salvaged from the existing cable.

## Analog Stick
> I am currently waiting on my parts to arrive to start developing this mod. More to come!

This is the mod that started this project, my Father-In-Law has parkinsons and has been using the Tartarus v2 to allow him to keep gaming, but the thumb-cluster/D-Pad would be much more useful if it were able to to analog input to replace the mouse allowing him to game with his good hand. This mod is a little more involved and is largely based on [Tuffrabit's](https://www.youtube.com/@tuffrabit) own Tartarus v2 mod

## D-Pad relocate
> This mod is still in the works to figure out how to make it simply and reversably. More to come!

This mod is an optional extra if you're doing the Analog Stick mod. The Tartarus v2 will work just fine with the D-Pad disconnected. You obviously won't be able to use those buttons, but everything else is unaffected. IF you want to keep those buttons around this is the mod for that. I'm still working out where it will be re-located. Tuffrabit acomplished this by adding a wing to the side of the device. I don't like this look, so I am currenlty investigating where I can place the buttons. This mod will likely be irreversable, and may use mechanical switches instead of the original D-Pad PCB.

## Full Mechanical Keyswitches
> I am currently waiting on my PCB and parts to be manufactured and delivered. I will update this section as I get parts and assemble everything. More to come!

This mod is a drop-in replacement for the existing mecha-membrane keyswitches Razer unfortunatley decided to ship this device with. It uses hotswapable Kailh Choc v2 keyswitches on a custom PCB and can be modified with your preferred keyswitch type.

## Top Thumb Button Mechanical Keyswitch
> I am currently waiting on my parts to arrive to start developing this mod. More to come!

I use the button above D-Pad as my 'space' or jump button because it is more ergonomic for me, however the tiny SMD button they use there is prone to double clicks and all manner of other issues that can negatively impact your gameplay. This mod will replace that button with the same low-profile keyswitches used in the Full Mechanical Keyswitches mod. I recommend doing this mod at the same time you do the Full Mechanical Keyswitches mod.

## Wireless
> This mod is still in the works to figure out how to make it simply and reversably. More to come!

This mod is the pipe-dream for me. I hate wires and anywhere I can eliminate them I will. The Full Mechanical Keyswitches mod used a Seeed Studio Xiao for the analog stick. My thought here is to piggy back off of it's wifi or bluetooth signals to provide a stable-reliable wireless connection to your PC. This will be a tricky mod and will likely be the last one updated here. I still need to figure out where the battery(s?) will go, as well as investigate wireless USB using the Seeed Studio Xiao to see if that is even possible. I recommend doing this mod at the same time you do the Full Mechanical Keyswitches mod.
