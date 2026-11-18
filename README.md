# Atlantic Flight Deck — A330 Simulator

A small, browser-first playable prototype for an A330-inspired flight simulator. It is intentionally dependency-free: open `index.html` in a modern browser to play.

## Play

- Use **Flight setup** to select one of six illustrative airports, destination, runway, starting position, difficulty, and weather.
- Click or move the thrust slider to enable synthesized engine audio (browser audio requires a user gesture).
- Keyboard: **↑/↓** pitch, **←/→** roll, **W/S** thrust, **B** parking brake, **G** landing gear, **F** flaps, **/** spoilers, **P** autopilot, **L** lights, **C** camera, **R** reset, **Space** pause.
- Choose Cockpit, Cabin, External, or Free cam in the lower-right view selector.
- Complete the practice checklist and use the Quick Start panel for a short takeoff guide.

## Current prototype

Includes a canvas-rendered airport scene, cockpit and external views, simplified flight dynamics, basic engine sound, six airport selections, runway selection, three difficulty labels, weather/time controls, flight-plan display, basic controls, and a practice checklist. The airport/route data and aircraft performance are illustrative. This is a game prototype, not a certified training aid or a source for real-world procedures/navigation.

## Next steps

A production-quality simulator would need a proper 3D engine and authored aircraft/airport assets, tested flight models, real navigation and airport data, detailed systems, controller/joystick mapping, and extensive performance and usability testing. This prototype prioritizes immediate playability and a low-friction browser start.
