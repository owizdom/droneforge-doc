# DroneForge Documentation

Hi DroneForge team. I'm Wisdom.

I spent a couple of days reading the public repos under [Droneforge-Inc](https://github.com/Droneforge-Inc) and [`nimbus_sdk`](https://github.com/droneforge/nimbus_sdk), watching the videos, and getting my hands on everything I could find about the team and DroneForge. So I built this. An unofficial Mintlify docs site for what's open. It is a work in progress. Plenty of pages still need shaping. A few claims still want measurement.

I love drones. I love agents. The way you put the two together is rare.

If anything in here is useful, please use it. If something is wrong or thin, tell me and I'll fix it.

Wisdom, [@owizdom](https://github.com/owizdom)

---

## Local preview

```bash
npm install -g mint
mint dev
```

Opens the docs at http://localhost:3000. Hot reload picks up edits as you save.

## Structure

Two tabs:

- **Documentation**, Get Started, Concepts, Build agents, Train policies, Resources.
- **Reference**, Hardware, Firmware, Flasher, Expression language, SDK & frames.

Theme matches [thedroneforge.com](https://thedroneforge.com): Bai Jamjuree, neon green on black, sharp rectangles, dark by default.

## What's documented

Every public repo in the [Droneforge-Inc](https://github.com/Droneforge-Inc) GitHub org plus [`droneforge/nimbus_sdk`](https://github.com/droneforge/nimbus_sdk):

- **firmware-flasher**, the `flash-helper` CLI for TX / RX / FC, plus `update.sh`.
- **ExpressLRS-Fork**, Nimbus TX hardware target, custom packet rates, telemetry frames.
- **betaflight-fork**, optical-flow driver, OPTRANGE telemetry, FC variants.
- **lerobot-fork**, dataset format and policy training pipeline.
- **nimbus_sdk**, desktop app UX, expression language, CRSF service.
- **docs**, the canonical Nimbus Map expression-language spec.

## License

Narrative prose is free to adapt. Code samples carry the license of their originating repo (GPL-3.0 for ELRS / Betaflight, Apache-2.0 for LeRobot).
